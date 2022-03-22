# Heroku Buildpack: PyPy-Side

Provide PyPy as an execuable to be invoked by app

## Description

This buildpack makes sure a PyPy executable is available on the dyno,
and that the environment variable `PYPY_EXECUTABLE` is set to point
to it when the app is run.

## Usage

Besides including the buildpack, add to the root folder of your repo
a file named `pypy-runtime.txt` with the name of the pypy version you
want to run. E.g. `pypy3.8-v7.3.7`

### Inspiration

Thanks [Daniel Weibel](https://github.com/weibeld/heroku-buildpack-run) and [Udi Oron](https://github.com/nonZero/heroku-cpython-pypy)



