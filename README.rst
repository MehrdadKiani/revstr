========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - |
        |
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/revstr/badge/?style=flat
    :target: https://revstr.readthedocs.io/
    :alt: Documentation Status

.. |version| image:: https://img.shields.io/pypi/v/revstr.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/revstr

.. |wheel| image:: https://img.shields.io/pypi/wheel/revstr.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/revstr

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/revstr.svg
    :alt: Supported versions
    :target: https://pypi.org/project/revstr

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/revstr.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/revstr

.. |commits-since| image:: https://img.shields.io/github/commits-since/MehrdadKiani/revstr/v1.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/MehrdadKiani/revstr/compare/v1.0.0...main



.. end-badges

Reverse a string

* Free software: MIT license

Installation
============

::

    pip install revstr

You can also install the in-development version with::

    pip install https://github.com/MehrdadKiani/revstr/archive/main.zip


Documentation
=============


https://revstr.readthedocs.io/


Development
===========

To run all the tests run::

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
