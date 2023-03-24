# Bitcoin vs Tweets; Effect on Market Capitalization. 

![alt text](https://github.com/agarcia0991/Project-4/blob/master/Resources/pexels-david-mcbee-730564.jpg?raw=true)

The goal of this project was to show if there was any correlation between activity on Twitter (total tweets/likes, and retweets having either hashtag of **#BTC** or **#Bitcoin**), and Bitcoin's market capitalization (market cap). For the machine learning (ML) portion of our project, we've used Linear Regression and the following three machine learing models to attempt to predict a future increase or decrease in Bitcoin's market cap. Market cap dataset contained prices beginning April 2013, and ending sometime in July of 2021. 


Bitcoin (BTC) Market cap data, from 2013 to 2021:
![alt text](https://github.com/agarcia0991/Project-4/blob/master/Images/all_data.PNG?raw=true)

## Machine Learning 
* Machine learning models were first **trained** on all market cap data before 2021; data was then **tested** with market cap data after January, 2021. 
![alt text](https://github.com/agarcia0991/Project-4/blob/master/Images/splittingData_Training_Testing.PNG?raw=true)

* Graph of autoregressing moving average (**ARMA**) model, with prediction:
![alt text](https://github.com/agarcia0991/Project-4/blob/master/Images/Predictions.PNG?raw=true)

* Graph of autoregressive integrated moving average (**ARIMA**) model's prediction:
![alt text](https://github.com/agarcia0991/Project-4/blob/master/Images/ARIMA.PNG?raw=true)

* Graph of seasonal autoregressive integrated moving average (**SARIMA**) model's predicion:
![alt text](https://github.com/agarcia0991/Project-4/blob/master/Images/SARIMA.PNG?raw=true)

* Of the four ML methods used, SARIMA took the longest to run and appeared to predict an increase in BTC price after 2021. 

## Conclusions

* We found that results differed significantly when training the ML models to inspect market cap data from 2017 and beyond, droping the front tail. 
With the training dates being less, and testing dates remaining the same, SARIMA then predicted that the price would decrease beyond 2021. 
* Our Twitter dataset was limited, in that it only contained tweet information from the year 2021. Therefore, we were not able to find a correlation between tweets (overall BTC buzz on Twitter), and Bitcoin's market cap and/or price. A larger dataset, containing tweets from more than one year, may provide better results. 
