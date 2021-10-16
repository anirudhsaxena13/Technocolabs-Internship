# PREDICTING THE VOLATALITY IN EQUITY MARKETS USING MACRO ECONOMIC HEADLINES

A) INTRODUCTON:

On June 2015, 2016 debt negotiations between Greek Govt and its creditors borke off abrubptly. Large market movements as a concequence of political and economic headlines are hardly uncommon, liquid markets are most suspectable to swing when the news breaks. Using VIX as a proxy for market volatality, we investigate how macroeconoic headlines affect the changes. Here, we predict equity market value using tweets from major news sources, investment banks and notable economists.

B) PROBLEM STATEMENT:

Twitter provides a plethora of market data. In this project we have extracted around 100,000 tweets from various accounts to predict the upward movements. Using this data we are researching how this economic news affects the market.

C) TYPE OF MACHINE LEARNING:

This project is Regression based problem, which is a predictive modelling technique that analyzes the relation between the target or dependent variable and independent variable in a dataset.

METRICS USED: The performance of a regression model must be reported as an error in those predictions and these error summarizes on average how close the predictions were to their expected values.

Accuracy mectrics we have used in this project are:

1.)Root Mean Squared Error(RMSE)
2.)Mean Absolute Error(MAE)
3.)Rsquared value(r2)

EXPLORATORY DATA ANALYSIS:

EDA includes extracting the twitter data based on the stock names viz, Apple, Tesla, Nvidia, Paypal and Microsoft, cleaning of twitter data that were pulled i.e., removing unnecessary data from tweets. After cleaning the data, below are the plots that were plotted against the sentiments that is Positive, Negative and Neutral.
![image](https://user-images.githubusercontent.com/72294006/137591036-dc71e556-07a4-429d-b7de-3e5c28c308f2.png)
