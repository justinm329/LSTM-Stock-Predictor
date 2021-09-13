# LSTM-Stock-Predictor

## Description
Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the Crypto Fear and Greed Index (FNG) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. My task is to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

## Objective
I used deep learning recurrent neural networks to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.

## Model Evaluations
* Which model has a lower loss?

If we look at both the models evaluation we can compare them and see that the stock predictor using the closing price had a lower loss. The loss for the closing price predictor was 0.053, and the fng predictor had a loss of 0.148. Based on these values we can conclude that the closing price had a lower loss.

* Which model tracks the actual values better over time?

Both of these models did not track the actual values the best however the predictor using the closing cost was better at predicting the actual values.


* Which window size works best for the model?

For both models a window of 1 worked best, however the closing predictor was better at predicting the 1 day window.

## Requirements
- [Python](https://www.python.org/)
- [Jupyter Lab](https://www.anaconda.com/)

## Libraries and Dependencies
- [numpy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [hvplot](https://hvplot.holoviz.org/)
- [tensorflow](https://www.tensorflow.org/)
- [keras](https://keras.io/)
- [sklearn](https://scikit-learn.org/stable/)

## Installations
"pip install pandas"

Numpy: 'pip install numpy'

Hvplot: 'pip install hvplot'

Tensorflow: 'pip install --upgrade tensorflow'

Keras: 'pip install keras'

Sklearn: 'pip install -U scikit-learn'

## Contact Informtion
- **Justin Farnan**
- **Email**: justinm329@yahoo.com
- **LinkedIn**: [LinkedIn](https://www.linkedin.com/in/justin-farnan/)
- **Medium**: [Medium](https://medium.com/@justinfarnan)
