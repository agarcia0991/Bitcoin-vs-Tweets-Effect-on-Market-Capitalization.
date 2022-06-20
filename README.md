# Project-4
## Bitcoin vs Tweets; Effect on Market Cap. 

![alt text](https://github.com/agarcia0991/Project-4/blob/master/Resources/pexels-david-mcbee-730564.jpg?raw=true)

* Bitcoin (BTC) Marketcap data, from 2013 to 2021.
![alt text](https://github.com/agarcia0991/Project-4/blob/master/Images/all_data.PNG?raw=true)

* For the machine learning (ML) portion of our project, we've used Linear Regression and the following: 
* ARMA - Autoregressive Moving Average
![alt text](https://github.com/agarcia0991/Project-4/blob/master/Images/Predictions.PNG?raw=true)

* ARIMA - Autoregressive Integrated Moving Average
![alt text](https://github.com/agarcia0991/Project-4/blob/master/Images/ARIMA.PNG?raw=true)

* SARIMA - Seasonal Autoregressive Integrated Moving Average
![alt text](https://github.com/agarcia0991/Project-4/blob/master/Images/SARIMA.PNG?raw=true)

* Of the four ML methods used, SARIMA took the longest to run and appeared to provide the best predictive results when training the data before 2019,
and testing the data after 2019. 

* We found that results differed significantly* when training the model to inspect marketcap data from 2017 and beyond, droping the front tail. 
*SARIMA then predicted that the price would decrese. 
