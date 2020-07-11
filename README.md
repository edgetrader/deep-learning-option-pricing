# Option Pricing and Implied Volatility computation using Deep Learning Model

## Summary
This repository contains analysese that attempts to value financial options and compute their implied volatility by means of Artificial Neural Networks. Details of the analysis can be found in respective notebooks

## Data
Option data are extracted using the ThinkOrSwim api. These are plain vanilla CALL and PUT equity options of all the securities in the Dow Jones Industrial Average which have 30 underlying securities. Each option type will have 20 strikes count at 2.5 intervals covering all Out-Of-The-Money, In-The_Money options.

## Analysis
1. [Option Pricing using Deep Learning Model](https://github.com/edgetrader/deep-learning-option-pricing/blob/master/notebook/deeplearning-option-pricing.ipynb)
2. [Option Implied Volatility using Deep Learning Model](https://github.com/edgetrader/deep-learning-option-pricing/blob/master/notebook/deeplearning-option-implied-vol.ipynb)
