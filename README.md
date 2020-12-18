# ada-2020-project-milestone-p3-p3_illusions
(Note: You can find most of our work in extension_project.ipynb. The model_selection.ipynb is a supplement to this file.)

## 1.Title
Predict the Pharmaceutical Stock Price with Google Trends Data

## 2.Abstract
In the paper the authors illustrated some simple forecasting methods, now since we have confirmed the usefulness of Google Trends data when predicting the present, we are wondering whether we can obtain ideal prediction results in other datasets.

Starting from this idea, combined with current social affairs, we are interested in medical-related topics during the pandemic. This year, the huge impact the pandemic has brought to the world is undeniable. This is not only reflected in the pharmaceutical industry, but also in financial fluctuations. Since the auto-regressive model is a very suitable model for stock price prediction, as an extension, we want to combine Google Trends data to explore the impact of relevant search keywords on the stock price of the pharmaceutical industry. So we take five most well-known stocks from the pharmaceutical industry as our new dataset, trying to use Google Trends data to predict the stock price and explore the impact of public opinion on public health on the pharmaceutical industry.

## 3.Research Questions
1) Which keywords in Google Trends data can be helpful in improving the prediction results?
2) Which categories in Google Trends data may can be helpful in improving the prediction results?
3) How do these Trends data correlate with the stock prices?

## 4.Proposed dataset
1) ***GlaxoSmithKline***, ***Johnson &Johnson***, ***Merck & Company, Inc.***, ***Pfizer, Inc.*** and ***Sanofi.*** stock price from 01-11-2010 to 01-11-2020. The data will be collected from ‘Yahoo! Finance’.
2) Three keywords data include ***vaccine***, ***virus*** and ***flu*** in Google Trends from 01-12-2019 to 01-12-2020.
3) Two categories data include ***health*** and ***finance*** in Google Trends from 01-12-2019 to 01-12-2020.

## 5.Methods
1) Data Collection: We will obtain the stock price dataset from ‘Yahoo! Finance’ and relevant Google Trends dataset from [Google Trends](https://trends.google.com/trends/?geo=US).

2) Base Prediction: Use the basic auto-regressive model to predict the fluctuations of the pharmaceutical stock prices.

3) Trends Prediction: Add the Google Trends data to the auto-regressive model, give a new prediction of the stock prices.

4) Comparison: Compare the MAE of the two different predicting ways above. Explore the impact of Google Trends data on the forecasting during some economic turning point periods.

## 6.Proposed timeline
Week 1: Working on individual replication

Week 2: Collecting the dataset from ‘Yahooh! Finance’ and ‘Google Trends’. Implementing the prediction with the new dataset. Experimenting on further improvements of the performance.

Week 3: Preparing the report and the video pitch 

## 7.Organization within the team
p4_Internal_milestone_1:

Finish of the individual replication (done individually)

p4_Internal_milestone_2:

Finish of extension analysis notebook (Yiwen Ma - data grabbing & data processing; Yiwen Ma/Junhong Li - build the model and make the prediction; Junhong Li/Zijun Cui - try different approaches to get further improvements of the model)

p4_Internal_milestone_3:

Finish of the report (Each team member should report their own part of work, Yiwen Ma/Zijun Cui will work on the rest such as introduction and conclusion, and review the whole paper)

p4_Internal_milestone_4:

Finish of the video pitch (Junhong Li wil prepare for the video pitch, Yiwen Ma/Zijun Cui will provide supports)
