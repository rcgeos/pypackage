# Cookiecutter PyPackage

[![image](https://github.com/giswqs/pypackage/workflows/build/badge.svg)](https://github.com/rcgeos/pypackage/actions?query=workflow%3Abuild)
[![image](https://github.com/giswqs/pypackage/workflows/docs/badge.svg)](https://rcgeos.github.io/pypackage)

[Cookiecutter](https://github.com/cookiecutter/cookiecutter) template for a Python package.

-   GitHub repo: <https://github.com/rcgeos/pypackage>
-   Documentation: <https://rcgeos.github.io/pypackage>
-   Free software: BSD license

## Features

-   Testing setup with `unittest` and `python setup.py test` or `pytest`
-   GitHub actions: Ready for GitHub Continuous Integration testing
-   [bump2version](https://github.com/c4urself/bump2version): Pre-configured version bumping with a single command
-   Auto-release to [PyPI](https://pypi.python.org/pypi) when you push a new tag to master (optional)
-   Command line interface using Click (optional) also

## Quickstart

Install the latest Cookiecutter if you haven't installed it yet (this
requires Cookiecutter 1.4.0 or higher):

    pip install -U cookiecutter

Generate a Python package project:

    cookiecutter gh:rcgeos/pypackage

Then:

-   Create a repo and put it there.
-   Go to [GitHub Settings - Workflow permissions](https://github.com/rcgeos/mapwidget/settings/actions) and enable Read and write permissions for GitHub Actions.
-   Install the dev requirements into a virtualenv. (`pip install -r requirements_dev.txt`)
-   [Register](https://packaging.python.org/tutorials/packaging-projects/#uploading-the-distribution-archives) your project with PyPI.
-   Release your package by pushing a new tag to master.
-   Add a `requirements.txt` file that specifies the packages you will
    need for your project and their versions. For more info see the [pip
    docs for requirements files](https://pip.pypa.io/en/stable/user_guide/#requirements-files).

Other options:

### Similar Cookiecutter Templates

-   [audreyfeldroy/cookiecutter-pypackage](https://github.com/audreyfeldroy/cookiecutter-pypackage): Cookiecutter template for a Python package.

### Fork This / Create Your Own

If you have differences in your preferred setup, I encourage you to fork
this to create your own version. Or create your own; it doesn't strictly
have to be a fork.

-   Once you have your own version working, add it to the Similar
    Cookiecutter Templates list above with a brief description.
-   It's up to you whether or not to rename your fork/own version. Do
    whatever you think sounds good.

### Or Submit a Pull Request

I also accept pull requests on this, if they're small, atomic, and if
they make my own packaging experience better.
