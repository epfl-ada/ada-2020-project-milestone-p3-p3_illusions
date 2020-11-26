# ada-2020-project-milestone-p3-p3_illusions

## 1.Title
#### Exploring the possibility of getting a better prediction with Google Trends by improving the baseline model

## 2.Abstract
###### In the paper the authors illustrated some simple forecasting methods, now since we have confirmed the usefulness of Google Trends data when predicting the present, we are wondering whether we can obtain better prediction results with some more sophisticated models. Starting from this idea, we propose to improve the original AR-1 model in two ways. One is to predict the present using continuous time-series data, namely the standard AR model. (In the paper the author only used data at (t - 1) and (t - 12).) Another one is to fit the data using a polynomial of degree N, and the value of N depends on the fitting results, which means that we’ll try different values of N to get the best prediction. Moreover, because we want to check if we can improve the prediction based on the paper, we will use the same dataset. We hope that we can explore more factors that affect forecasts through these efforts.

## 3.Research Questions
###### 1) Will a more sophisticated AR model improve the prediction? (feature augmentation)
###### 2) Will Polynomial Regression have better performance than linear regression in this case or in the case, overfitting may result in higher MAE? (ploy instead of linear)

## 4.Proposed dataset
###### merged_autos.csv, including sales, suvs in Goole Trends and insurance in Google Trends from 2004-1-1 to 2011-7-1

## 5.Methods
###### 1) Instead of the AR model used in the paper, we plan to use an AR-12 model. We plan to use a sequence of values from (t-12) to (t-1) (12-month data) instead of only (t-12) and (t-1) (2-month data) and Google Trends variables to replicate the prediction process to see whether it can improve the results.
###### 2) The regression model used in the paper is a linear model and the authors said that they just try to introduce a baseline to use Google Trends data. We plan to introduce a polynomial regression in the case and try to find out whether it will improve the results.

## 6.Proposed timeline
######  Nov 27 - Start of the project p4 milestone
######  |———Working on individual replication &
######  |———Exploring in the improvement of the methods
######  Dec 6   - Finish of Individual replication
######  |———Implementing in the improvement of the methods
######  Dec 12 - Finish of extension analysis notebook
######  |———Preparing the data story, the report, and the video pitch
######  Dec 18 - Submitting the deliverables

## 7.Organization within the team
###### p4_Internal_milestone_1 - Finish of the individual replication (done individually)
###### p4_Internal_milestone_2 - Finish of extension analysis notebook (two team members work on one of the two methods proposed respectively, the third team member helps with review and reorganization)
###### p4_Internal_milestone_3 - Finish of the data story (member A & member B)
###### p4_Internal_milestone_4 - Finish of the report (member A & member C)
###### p4_Internal_milestone_5 - Finish of the video pitch (member B & member C)

## 8.Questions for TAs (optional)
###### Add here any questions you have for us related to the proposed project.
