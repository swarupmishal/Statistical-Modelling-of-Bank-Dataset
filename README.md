# Statistical Modelling for Churn investigation
![alt text](https://github.com/swarupmishal/Statistical-Modelling-for-Churn-investigation/blob/master/Extras/AAEAAQAAAAAAAAdeAAAAJDRmOWNmYTdhLTRhNmUtNGZlYi05MjIwLTQ3YTRhODZmNTQ2YQ.jpg)


## What exactly the Data is?
Its a large dataset with 10000 records of a list of customers of a Bank. Bank is recently facing a problem that a lot of its customers are leaving the Bank. The dataset contains details like CustomerID, CreditScore, Geography, Age, Tenure, Balance, NumberOfProducts, IsActiveMember, EstimatedSalary and if the customer has excited the bank or not. We are trying to analyze what type of customers are most likely to leave the Bank.


## How can one obtain the Data?
Get the dataset using the following links:

Train: http://www.superdatascience.com/wp-content/uploads/2015/08/Churn-Modelling.csv

Test: http://www.superdatascience.com/wp-content/uploads/2015/08/Churn-Modelling-Test-Data.csv

## How have we tackled the problem?
We have built a complete robust Geodemographic Segmentation Model for Churn Investigation of a Bank dataset. 
1. Preprocessed the data using Excel, SSIS and SSMS. 
2. Applied Logistic Regression using backward elimination, transformed independent variables, created derived variables, checked for multicollinearity in Gretl. 
3. Drew Cumulative Accuracy Profile curve for the model in Excel.
4. Applied the model on the test data with a reduction in accuracy of only 3%.

The model summary can be found here: https://github.com/swarupmishal/Statistical-Modelling-for-Churn-investigation/blob/master/Output/Model%2020.docx

### Cap Curve of Train dataset
![alt text](https://github.com/swarupmishal/Statistical-Modelling-for-Churn-investigation/blob/master/Output/Train%20data%20CAP%20curve.png)

### Cap Curve of Test dataset
![alt text](https://github.com/swarupmishal/Statistical-Modelling-for-Churn-investigation/blob/master/Output/Test%20data%20CAP%20curve.png)

We got an accuracy of 96% on test data with respect to train data. 

The final report can be found here: https://github.com/swarupmishal/Statistical-Modelling-for-Churn-investigation/blob/master/Final%20Report/Report.csv


## Conclusion
Thus from the final report we can conclude that the most significant variables are IsActiveMember, Female and Germany. If the customer is more active he is most likely to stay, whereas if the customer is Female or from Germany, he/she is more likely to exit the Bank. The Bank should really consider doing something for these customers.
