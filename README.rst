========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - |github-actions| |codecov| |scrutinizer|
    * - package
      - |version| |wheel| |supported-versions| |supported-implementations| |commits-since|
.. |docs| image:: https://readthedocs.org/projects/sqli-dpsda_tabular/badge/?style=flat
    :target: https://readthedocs.org/projects/sqli-dpsda_tabular/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/Gasyd0/sqli-dpsda_tabular/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/Gasyd0/sqli-dpsda_tabular/actions

.. |codecov| image:: https://codecov.io/gh/Gasyd0/sqli-dpsda_tabular/branch/main/graphs/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://app.codecov.io/github/Gasyd0/sqli-dpsda_tabular

.. |version| image:: https://img.shields.io/pypi/v/dpsda-tabular.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/dpsda-tabular

.. |wheel| image:: https://img.shields.io/pypi/wheel/dpsda-tabular.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/dpsda-tabular

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/dpsda-tabular.svg
    :alt: Supported versions
    :target: https://pypi.org/project/dpsda-tabular

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/dpsda-tabular.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/dpsda-tabular

.. |commits-since| image:: https://img.shields.io/github/commits-since/Gasyd0/sqli-dpsda_tabular/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/Gasyd0/sqli-dpsda_tabular/compare/v0.0.0...main


.. |scrutinizer| image:: https://img.shields.io/scrutinizer/quality/g/Gasyd0/sqli-dpsda_tabular/main.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/Gasyd0/sqli-dpsda_tabular/


.. end-badges

This project involves in applying Differencial Private Synthetic Data via Foundation Model APIs (DPSDA) on tabular data
(texts).

Installation
============

::

    pip install dpsda-tabular

You can also install the in-development version with::

    pip install https://github.com/Gasyd0/sqli-dpsda_tabular/archive/main.zip


Documentation
=============


https://sqli-dpsda_tabular.readthedocs.io/


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
