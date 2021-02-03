# Modelling-of-Bitcoin-Price-Prediction-Using-Deep-Learning
Forecasting the future has always been a difficult task. The importance of predicting the future has been getting a primary role in the field of computer science and information technology. Developing several algorithms and building it to forecast future events has been paid a significant amount of attention since the past decade. Here, we use one of the latest and most advanced technologies i.e. Deep Learning. The main aim of this project is to showcase how a trained machine model can forecast the future fluctuations in the rise of cryptocurrencies like bitcoin. It shows how a trained machine model can give the price of a cryptocurrency like bitcoin if we give the right amount of data and sufficient computational power. What we expect as the ouput is a graph with the predicted values. The most popular and widely used technology is the kind of technological solution that could help the humankind to predict the future events. Here, we collect the previous values of bitcoin from various bitcoin exchanges. So, with the vast amount of data generated, we segregate the values and try to forecast the bitcoin prices in the form of a graph. We use Recurrent Neural Networks(RNN) for this deep learning methodology. This can be achieved by using several machine learning techniques and methodologies.
Summary
---
[LSTM](https://en.wikipedia.org/wiki/Long_short-term_memory) (Long Short-Term Network) is a kind of Recurrent Neural Network which used in the field of deep learning. Traditional neural networks can't remember previous inputs. But Recurrent Neural Networks enable us to learn from previous sequence input datas. A LSTM unit is composed of a cell, an input gate, an output gate and a forget gate.

In this repository was written a Bitcoin Price Prediction project based on Google Trend keywords by using LSTM algorithm and Python 3.6 version. Here we tried to determine, "Does LSTM algorithm predict Bitcoin Close price by adding many keywords volume from Google Trends". Bitcoin price dataset was downloaded hourly using coinapi.io API and Google Trends keywords were downloaded hourly using Python pytrend library. Finally chosen Bitcoin, BTC, Blockchain, Cryptocurrency and Iota keywords were added as columns into dataset.
Consequently LSTM algorithm predicted Bitcoin Close prices better than we expected by improving its learning in every epoch. The result images are shown following.

Images
---
Prediction Plot<br/>
<img src="/images/3D-PredictionPlot.png"  />
Result of loss value after every epoch<br/>
<img src="/images/3D-LossValuePlot.png" />
Distribution of columns <br/>
<img src="/images/3D-DistributionColumns.png" />


Recurrent Neural Network (RNN), LSTM (Long Short-Time Memory), Artifical Intelligence, Deep Learning, Prediction, Bitcoin, Google Trends 
