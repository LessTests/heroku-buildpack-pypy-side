# Heroku Buildpack: PyPy-Side

Provide PyPy as an execuable to be invoked by app

## Description

This buildpack makes sure a PyPy executable is available on the dyno,
and that the environment variable `PYPY_EXECUTABLE` is set to point
to it when the app is run.

## Usage

Just include the buildpack in your `app.json`

### Inspiration

Thanks [Daniel Weibel](https://github.com/weibeld/heroku-buildpack-run) and [Udi Oron](https://github.com/nonZero/heroku-cpython-pypy)



