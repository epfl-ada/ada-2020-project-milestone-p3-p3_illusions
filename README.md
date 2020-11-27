# ada-2020-project-milestone-p3-p3_illusions

## 1.Title
###### Predict the pharmaceutical stock price with Google Trends data

## 2.Abstract
###### In the paper the authors illustrated some simple forecasting methods, now since we have confirmed the usefulness of Google Trends data when predicting the present, we are wondering whether we can obtain ideal prediction results in other datasets.
###### Starting from this idea, combined with current social affairs, we are interested in the development of the pharmaceutical industry during the pandemic. So we take Pfizer Inc. stock price as our new dataset, trying to use Google Trends data to predict the stock price and explore the impact of public opinion on public health on the pharmaceutical industry.
###### Moreover, since the models the authors used were simple, we plan to predict the present with some more sophisticated models to check if we can get better results. We propose to improve the original AR-1 model in two ways. One is to predict the present using continuous time-series data, namely the standard AR model. (In the paper the author only used data at (t - 1) and (t - 12).) Another one is to fit the data using a polynomial of degree N, and the value of N depends on the fitting results, which means that we’ll try different values of N to get the best prediction. We hope that we can explore more factors that affect forecasts through these efforts.


## 3.Research Questions
###### 1) What Google Trends data should we choose to improve prediction results?
###### 2) How to struct a proper AR-P model for the new dataset?
###### 3) Will Polynomial Regression have a better performance than linear regression or not? (considering the possibility of overfitting)

## 4.Proposed dataset
###### - Pfizer Inc. (PFE) stock price from 01-11-2010 to 01-11-2020. The data will be collected from “Yahoo! Finance”.
###### - ‘vaccine’, ‘virus’, ‘flu’ in Google Trends from 01-11-2010 to 01-11-2020.

## 5.Methods
###### 1）Data Collection: We will get the stock price dataset from “Yahoo! Finance” and relevant google trends dataset from ‘Google Trends’ (https://trends.google.com/trends/?geo=US)
###### 2）We will try the process introduced in the paper based on another financial dataset. We would like to do out-sample prediction of base prediction and google trends prediction. Then, we can compare the results with actual data to find whether google trends variables could improve the prediction result.
###### 3) Instead of the AR model used in the paper, we plan to use an AR-12 model. We plan to use a sequence of values from (t-12) to (t-1) (12-month data) instead of only (t-12) and (t-1) (2-month data) and Google Trends variables to replicate the prediction process to see whether it can improve the results.
###### 4) The regression model used in the paper is a linear model and the authors said that they just try to introduce a baseline to use Google Trends data. We plan to introduce a polynomial regression in the case and try to find out whether it will improve the results.

## 6.Proposed timeline
###### Week 1: Working on individual replication
###### Week 2: Collecting the dataset from ‘Yahooh! Finance’ and ‘Google Trends’. Implementing the prediction with the new dataset. Experimenting on further improvements of the performance.
###### Week 3: Preparing the report and the video pitch 

## 7.Organization within the team
###### p4_Internal_milestone_1 - Finish of the individual replication (done individually)
###### p4_Internal_milestone_2 - Finish of extension analysis notebook (Yiwen Ma - data grabbing & data processing; Yiwen Ma/Junhong Li - build the model and make the prediction; Junhong Li/Zijun Cui - try different approaches to get further improvements of the model)
###### p4_Internal_milestone_3 - Finish of the report (Each team member should report their own part of work, Yiwen Ma/Zijun Cui will work on the rest such as introduction and conclusion, and review the whole paper)
###### p4_Internal_milestone_4 - Finish of the video pitch (Junhong Li wil prepare for the video pitch, Yiwen Ma/Zijun Cui will provide supports)


## 8.Questions for TAs (optional)
###### We are not sure about if it makes sense to use Google Trends data as ‘vaccine’ and ‘flu’ to predict the stock price in medical industry? 
