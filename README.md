# Option Pricing using Deep Learning Model
Option Pricing using Deep Learning Model

## Summary
This analysis attempts to value financial options by means of Artifical Neural Networks. Using Tensorflow and Keras libraries to train a deep learning regression model on the following features:
- Strike Price of an option
- Current Price of the underlying stock
- Time to expiration
- Volatility of underlying stock
- Option Type - Call / Put

and targeting the current option price.  As the model is traded on observable prices and option attributes, I assume all other analytics and assumptions are reflected in the option prices.  The model will be trained and adjust its model weights accordingly.

## Analysis
See the analysis [here](https://github.com/edgetrader/deep-learning-option-pricing/blob/master/notebook/deeplearning-option-pricing.ipynb).
