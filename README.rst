========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-pylibrary-example-bcs/badge/?style=flat
    :target: https://readthedocs.org/projects/python-pylibrary-example-bcs
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/BrendanSweeny/python-pylibrary-example-bcs.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/BrendanSweeny/python-pylibrary-example-bcs

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/BrendanSweeny/python-pylibrary-example-bcs?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/BrendanSweeny/python-pylibrary-example-bcs

.. |requires| image:: https://requires.io/github/BrendanSweeny/python-pylibrary-example-bcs/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/BrendanSweeny/python-pylibrary-example-bcs/requirements/?branch=master

.. |codecov| image:: https://codecov.io/gh/BrendanSweeny/python-pylibrary-example-bcs/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/BrendanSweeny/python-pylibrary-example-bcs

.. |version| image:: https://img.shields.io/pypi/v/pylibrary-example-bcs.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/pylibrary-example-bcs

.. |wheel| image:: https://img.shields.io/pypi/wheel/pylibrary-example-bcs.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/pylibrary-example-bcs

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/pylibrary-example-bcs.svg
    :alt: Supported versions
    :target: https://pypi.org/project/pylibrary-example-bcs

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/pylibrary-example-bcs.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/pylibrary-example-bcs

.. |commits-since| image:: https://img.shields.io/github/commits-since/BrendanSweeny/python-pylibrary-example-bcs/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/BrendanSweeny/python-pylibrary-example-bcs/compare/v0.0.0...master



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: GNU Lesser General Public License v3 or later (LGPLv3+)

Installation
============

::

    pip install pylibrary-example-bcs

You can also install the in-development version with::

    pip install https://github.com/BrendanSweeny/python-pylibrary-example-bcs/archive/master.zip


Documentation
=============


https://python-pylibrary-example-bcs.readthedocs.io/


Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
