# Project-4
## Bitcoin vs Tweets; Effect on Market Cap. 

![alt text](https://github.com/agarcia0991/Project-4/blob/master/Resources/pexels-david-mcbee-730564.jpg?raw=true)

The goal of this project was to show if there was any correlation between tweets on Twitter, and Bitcoin's marketcap. For the machine learning (ML) portion of our project, we've used Linear Regression and the following three models:
* ARMA - Autoregressive Moving Average
* ARIMA - Autoregressive Integrated Moving Average
* SARIMA - Seasonal Autoregressive Integrated Moving Average

Bitcoin (BTC) Marketcap data, from 2013 to 2021:
![alt text](https://github.com/agarcia0991/Project-4/blob/master/Images/all_data.PNG?raw=true)

# Machine Learning 

* Graph of ARMA with prediction:
![alt text](https://github.com/agarcia0991/Project-4/blob/master/Images/Predictions.PNG?raw=true)

* Graph of ARIMA model's prediction:
![alt text](https://github.com/agarcia0991/Project-4/blob/master/Images/ARIMA.PNG?raw=true)

* Graph of SARIMA model's predicion:
![alt text](https://github.com/agarcia0991/Project-4/blob/master/Images/SARIMA.PNG?raw=true)

* Of the four ML methods used, SARIMA took the longest to run and appeared to predict an increase in BTC price, after 2021; when training the data before 2019,
and testing the data after 2019. 

* We found that results differed significantly* when training the model to inspect marketcap data from 2017 and beyond, droping the front tail. 
*SARIMA then predicted that the price would decrese. 
