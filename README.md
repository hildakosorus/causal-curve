# causal-curve
Python tools to perform causal inference using observational data when the treatment of interest is continuous.


<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/e/e8/Antikythera_mechanism.svg" align="middle" width="350" height="477" />
</p>


[The Antikythera mechanism](https://en.wikipedia.org/wiki/Antikythera_mechanism), an ancient analog computer, with lots of beautiful curves.




## Table of Contents

- [Overview](#overview)
- [Documentation](#documentation)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [References](#references)

## Overview

There are many implemented methods to perform causal inference when your intervention of interest is binary,
but few methods exist to handle continuous treatments.

This is unfortunate because there are many scenarios (in industry and research) where these methods would be useful.
For example, when you would like to:

* Estimate the causal response to increasing or decreasing the price of a product across a wide range.
* Understand how the number of hours per week of aerobic exercise causes positive health outcomes.
* Estimate how decreasing order wait time will impact customer satisfaction, after controlling for confounding effects.
* Estimate how changing neighborhood income inequality (Gini index) could be causally related to neighborhood crime rate.

This library attempts to address this gap, providing tools to estimate causal curves (AKA causal dose-response curves).

## Documentation

TBC

## Installation

TBC

## Usage

TBC

## Contributing

Your help is absolutely welcome! Please do reach out or create a feature branch!

## References

Galagate, D. Causal Inference with a Continuous Treatment and Outcome: Alternative
Estimators for Parametric Dose-Response function with Applications. PhD thesis, 2016.

Moodie E and Stephens DA. Estimation of dose–response functions for
longitudinal data using the generalised propensity score. In: Statistical Methods in
Medical Research 21(2), 2010, pp.149–166.

Hirano K and Imbens GW. The propensity score with continuous treatments.
In: Gelman A and Meng XL (eds) Applied bayesian modeling and causal inference
from incomplete-data perspectives. Oxford, UK: Wiley, 2004, pp.73–84.
