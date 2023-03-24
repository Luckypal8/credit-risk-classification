Credit Risk Analysis Report 

In this assignment, I have used Python to evaluate several machine learning models to predict credit risk. The dataset is of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

We adopted the following procedure:

Split the data into training and testing sets
Created a logistic regression model with original data.
Calculates the accuracy score of the model.
Generates a confusion matrix.
Printed the classification report.


In the first test, accuracy score is 99%.
The high_risk precision is still 1% only with 95% sensitivity which makes a F1 of 1%.
The model does predict both healthy loan and high risk loan well because of the high accuracy and F-1 and recall scores.

I repeated the same with resampled data using RandomOverSampler Model.



The balanced accuracy score is 99%.
The high_risk precision is about 1% 
The model does predict both healthy loan and high risk loan well because of the high accuracy and F-1 and recall scores.