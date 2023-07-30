<div align="center">
    <p>
        <img src="./data/logo/logo.png">
    </p>

<h2 align="center">Factor Risk Modeling</h4>
<h4 align="center">The FactorRiskModeling package is a Python library designed to facilitate the modeling and analysis of factor risks associated with stocks.</h4>
<h5 align="center">[v-2023.7.0]</h5>

<p align="center">
  <a href="#introduction">Introduction</a> •
  <a href="#installation">Installation</a> •
  <a href="#installation">Documentation</a> •
  <a href="#installation">Development</a>
</p>
</div>

# Overview

The FactorRiskModeling package is a Python library designed to facilitate the modeling and analysis of factor risks
associated with stocks.


# Installation

```cmd
> pip install FactorRiskModeling
```

You can also install the stable version with

```cmd

>>> pip install https://github.com/ibaris/factor-risk-modeling/archive/main.zip

```

To install the in-development version, change the branch name main to the other
available branch names.

# Documentation

The documentation `code` documentation is in `build/docs`.

# Development

To run all the tests and to build the `code` documentation run

```cmd
>>> tox
```

Note, to combine the coverage data from all the tox environments run:

```cmd
>>> set PYTEST_ADDOPTS=--cov-append
>>> tox
```

for Windows and

```cmd
>>> PYTEST_ADDOPTS=--cov-append tox
```

for Linux.
