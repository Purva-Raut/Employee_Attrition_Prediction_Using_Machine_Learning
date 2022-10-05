# Employee_Attrition_Prediction_Using_Machine_Learning

#Problen Statement and Business Case
Hiring and re-training employees is expensive and time consuming.
It would be great if we get to know the reasons why employees are more likely to leave the company so that companies can work on it.
It would also be helpful to predict which employees are likely to leave based on the different features so that companies are more prepared.

I did dataanalysis to analyse the reasons for employee and attrition and machine learning using Logistic Regression and Xgboost to predict which employees are more likely to quit based on the different features.

# The steps involved were:
1. Importing libraries
2. Importing Data
3. Data Cleaning
4. Exploratory Data Analysis
5. Data Visualisation
6. Drawing Conclusions based on our analysis
7. Create Input and Output Dataset (Convery Cat variables to numeric using One Hot Encoder)
8. Scaling the Data
9. Splitting training and testing data
10. Predictions
11. Checking Accuracy
12. Compare Models(Logistic Regression and Xgboost) using Confusion Matrix

# Data Insights:
1. Mean Age, Daily Rate, EnvironmentSatisfaction, JobSatisfaction,StockOptionLevel of employees who stayed was observed to be higher than those who left.
2. Distance from home of employees who stayed was observed to be shorter than those who left.
3. Frequent business travel could be the reason for attrition
4. Employees with the least Job Involvement, Job Level, RelationshipSatisfaction, work life balance show more attrition rate
5. Sales Representatives, Single employees, Employees who work overtime, employees worked in many companies show a higher attrition rate.
6. As Monthly Income increases the number of people left tend to be lower compared to the no. of people who stayed.
7. As Total working years increases the number of people stayed tend to be higher compared to the no. of people who left uptil 40 years. After 40 years people leaving are more.This might be due to retirement.
8. Employees who stay longer in the current role tend to stay.
9. As Years with the current manager increases the number of people stayed tend to be higher compared to the no. of people who left.

# Recommendations:
1. Survey can be conducted to find and provide better EnvironmentSatisfaction, JobSatisfaction, RelationshipSatisfaction, WorkLifeBalance for the employees.
2. Keep moderate business travel ,JobInvolvement and minimum Overtime
3. Schedule a meeting with Sales Representatives to find the challenged faced by them.
4. Features such as age, marital status, NumCompaniesWorked, TotalWorkingYears should be used for study purpose only and not to make decisions for recruitment of employees as to maintain unbiased recruitment process.

# Model Buiding Insights:
1. Both models -Logistic Regression and XGBoost showed good accuracy >80%.
2. No. of samples misclassified by XGboost algorithm are slightly more than those of Logistic Regression algorithm.
3. This indicates that the Logistic Regression Classifier Model is better than XGboost algorithm
