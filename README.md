Heroku buildpack: OpenCV
=======================

A Heroku buildpack that installs OpenCV (currently v3.4.1) shared libs, and then exports include and lib paths to `INCLUDE_PATH` and `LIBRARY_PATH` on the build dyno, and `LD_LIBRARY_PATH` on the production dyno.

