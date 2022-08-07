=======================
Python project template
=======================

Relies on `pip-compile` provided by the `pip-tools` package. Add your runtime dependencies to `requirements.txt`
and your additional development dependencies to `requirments-dev.txt`.

Contains basic contiguration for `black`, `isort` and `flake8`.

Defaults
========

Python 3.10, the latest at the time of writing.

Maximum line length is 99 characters, the maximum allowed by pep-8.

Expects the python code in the `src` folder, which seems to be the winning layout in the python world & recommended by packaging.python.org.
