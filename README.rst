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

.. |docs| image:: https://readthedocs.org/projects/python-snakespit/badge/?style=flat
    :target: https://readthedocs.org/projects/python-snakespit
    :alt: Documentation Status

.. |version| image:: https://img.shields.io/pypi/v/snakespit.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/snakespit

.. |commits-since| image:: https://img.shields.io/github/commits-since/dohlee/python-snakespit/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/dohlee/python-snakespit/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/snakespit.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/snakespit

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/snakespit.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/snakespit

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/snakespit.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/snakespit


.. end-badges

Get snakemke rules with ease.

* Free software: MIT license

Installation
============

::

    pip install snakespit

Documentation
=============

https://python-snakespit.readthedocs.io/

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
