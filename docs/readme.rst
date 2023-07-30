========
Overview
========
Factor Risk Modeling [v-2023.7.0]


.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests

.. |docs| image:: https://readthedocs.org/projects/factor-risk-modeling/badge/?style=flat
    :target: https://factor-risk-modeling.readthedocs.io/
    :alt: Documentation Status

.. |commits-since| image:: https://img.shields.io/github/commits-since/ibaris/factor-risk-modeling/v2023.7.0.svg
    :alt: Commits since latest release
    :target: https://github.com/ibaris/factor-risk-modeling/compare/v2023.7.0...main


.. end-badges

The FactorRiskModeling package is a Python library designed to facilitate the modeling and analysis of factor risks
associated with stocks.

Installation
============

::

    pip install FactorRiskModeling

You can also install the in-development version with::

    pip install https://github.com/ibaris/factor-risk-modeling/archive/main.zip


Documentation
=============


https://factor-risk-modeling.readthedocs.io/


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
