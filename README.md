# Black-Scholes-Merton Model Calculator

This repository contains a Jupyter Notebook that implements the Black-Scholes-Merton model to calculate option premiums and the Greeks for European-style options.

## Description

The Black-Scholes-Merton model is a mathematical model for pricing an options contract. In this implementation, we compute the theoretical price of European call and put options and their Greeks - Delta, Gamma, Vega, Theta, and Rho.

## Features

- Calculation of call and put option premiums using the Black-Scholes formula.
- Computation of Greeks which measure the sensitivity of the option's value to the following:
  - Delta: Underlying asset price changes.
  - Gamma: Delta changes.
  - Vega: Volatility changes.
  - Theta: Time decay.
  - Rho: Interest rate changes.

## Requirements

To run this notebook, you need to have the following packages installed:
- `numpy`
- `scipy`
- `matplotlib` (optional, for plotting)

You can install these packages using `pip`:

## Usage

To use this calculator:

1. Clone this repository to your local machine.
2. Open the `Black_Scholes_Merton_Model.ipynb` file in Jupyter Notebook or JupyterLab.
3. Follow the instructions in the notebook to enter the required parameters for your options calculations.
