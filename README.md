# Parallax Distance Estimation with Bayesian Priors

This repository contains a Python script that estimates the distance of astronomical objects based on their parallax measurements using Bayesian inference. The script uses three different priors (uniform, constant volume density, and exponentially decreasing volume density) to calculate the posterior distributions of the distance.

## Features
- Reads parallax data from a CSV file (e.g., from Gaia's archive).
- Implements three prior models for Bayesian analysis:
  1. **Uniform Prior**: Assumes a uniform distribution over the range of possible distances.
  2. **Constant Volume Density Prior**: Assumes a constant volume density distribution, proportional to \(x^2\).
  3. **Exponentially Decreasing Volume Density Prior**: Assumes an exponentially decreasing density distribution.
- Uses Gaussian likelihood based on the parallax and its error.
- Outputs posterior distributions for each prior.
- Visualizes the results with **matplotlib** in 3 subplots comparing the prior, likelihood, and posterior distributions.

## Requirements
- **Python 3.x**
- **NumPy**
- **Matplotlib**
- **SciPy**
- **Pandas**

To install the required packages, you can use the following command:

```bash
pip install numpy matplotlib scipy pandas

