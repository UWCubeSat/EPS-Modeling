# EPS-Modeling

## Setup

```bash
pip install -r requirements.txt
```

## Overview

Using PyBaMM to model HS2's battery pack. Currently working on:

- Using Bayesian hyperparameter tuning to tweak parameter values to produce better pybamm models for our batteries/test data
- Incorporating battery degradation mechanisms
- Creating a more streamlined way to turn requirements into a subsystem schedule
- Simulating longer experiments (weeks/months in orbit)

> [!NOTE] We previously used `liionpack` to model larger battery packs - this package is no longer being maintained, and has issues with newer versions of Python. Going forward, this repo exclusively uses `pybamm`.
