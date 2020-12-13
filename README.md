<img src="docs/img/logo_large.png" width="120" align="right">

[![pytest](https://github.com/ing-bank/probatus/workflows/Unit%20tests/badge.svg)](https://github.com/ing_rpaa/probatus/actions)
[![coverage report](https://gitlab.com/ing_rpaa/probatus/badges/master/coverage.svg)](https://gitlab.com/ing_rpaa/probatus/-/commits/master)
[![PyPi Version](https://img.shields.io/pypi/pyversions/probatus)](#)
[![PyPI](https://img.shields.io/pypi/v/probatus)](#)
[![PyPI - Downloads](https://img.shields.io/pypi/dm/probatus)](#)

# Probatus

## Overview

**Probatus** is a python package that helps validate binary classification models and the data used to develop them. Main features:

- [probatus.interpret](https://ing-bank.github.io/probatus/api/model_interpret.html) provides shap-based model interpretation tools 
- [probatus.metric_volatility](https://ing-bank.github.io/probatus/api/metric_volatility.html) provides tools using bootstrapping and/or different random seeds to assess metric volatility/stability.
- [probatus.sample_similarity](https://ing-bank.github.io/probatus/api/sample_similarity.html) helps to comparing two datasets using resemblance modelling, f.e. to compare `train` with out-of-time `test`.
- [probatus.feature_elimination.ShapRFECV](https://ing-bank.github.io/probatus/api/feature_elimination.html) provides cross-validated Recursive Feature Elimination using shap feature importance.

## Installation

In order to install probatus you need to use Python 3.6 or higher.

You can install probatus using pip:

```bash
pip install probatus
```

Alternatively you can fork/clone and run:

```bash
git clone https://gitlab.com/ing_rpaa/probatus.git
cd probatus
pip install .
```

## Documentation

Documentation available at [ing-bank.github.io/probatus/](https://ing-bank.github.io/probatus/).

## Contribution

To learn more about making a contribution to probatus, please see [`CONTRIBUTING.md`](CONTRIBUTING.md).
