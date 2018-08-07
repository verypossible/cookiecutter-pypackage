Very PyPackage
======================
Minimal [cookiecutter](https://github.com/audreyr/cookiecutter) template for
Very-style Python packages, forked from
[cookiecutter-pypackage](https://github.com/audreyr/cookiecutter-pypackage)
-   Free software: BSD license

Features
--------

-   Testing setup with `pytest`
-   [CircleCI 2.0](https://circleci.com/): Ready for Circle Continuous
    Integration testing.
-   Auto-release to [PyPI](https://pypi.python.org/pypi) when you push a
    new tag to master (optional)
-   Command line interface using Click (optional)

Quickstart
----------

Install the latest Cookiecutter if you haven't installed it yet (this
requires Cookiecutter 1.4.0 or higher):

```
pip install -U cookiecutter
```

or

```
brew install cookiecutter
```

Generate a Python package project:

```
cookiecutter https://github.com/verypossible/very_pypackage
```

Then:

-   Create a repo and put it there.
-   Add the repo to [CircleCI](https://circleci.com/).
-   Register your project with PyPI: `python setup.py register`
-   Release your package by pushing a new tag to master.
