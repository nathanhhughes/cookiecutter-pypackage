======================
Cookiecutter PyPackage
======================

Cookiecutter_ template for a Python package, forked from `briggySmalls/cookiecutter-pypackage`_.

* GitHub repo: https://github.com/nathanhhughes/cookiecutter-pypackage/
* Free software: BSD license

.. _briggySmalls/cookiecutter-pypackage: https://github.com/briggySmalls/cookiecutter-pypackage
.. _Cookiecutter: https://github.com/audreyr/cookiecutter

Features
--------

This template is based on `_briggySmalls/cookiecutter-pypackage`_, but makes a few changes:

* Linting only provided by flake8_ [executed by Tox]
* Formatting provided by black_ and isort_ [checked by Tox]
* isort_ and flake8_ configuration to deconflict from black_
* Napoleon sphinx extension automatically added (not optional)
* ReadTheDocs sphinx format is the default style for sphinx
* No Travis or Appveyor support for this repo
* No travis or pyup support in the template

Quickstart
----------

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    pip install -U cookiecutter

Generate a Python package project::

    cookiecutter https://github.com/nathanhhughes/cookiecutter-pypackage.git

Then:

* Create a repo and put it there.
* Install the dev requirements into a virtualenv. (``poetry install``)
* Release your package by pushing a new tag to master.
* Get your code on! Add your package dependencies as you go, locking them into your virtual environment with ``poetry add``.

.. _Register: https://packaging.python.org/tutorials/packaging-projects/#uploading-the-distribution-archives

.. _invoke: http://www.pyinvoke.org/
.. _isort: https://pypi.org/project/isort/
.. _black: https://github.com/psf/black
.. _flake8: https://pypi.org/project/flake8/
.. _poetry: https://python-poetry.org/
.. _original_pypackage: https://github.com/briggySmalls/cookiecutter-pypackage/
.. _Tox: http://testrun.org/tox/
.. _Sphinx: http://sphinx-doc.org/
.. _Read the Docs: https://readthedocs.io/
.. _bump2version: https://github.com/c4urself/bump2version
.. _PyPi: https://pypi.python.org/pypi
