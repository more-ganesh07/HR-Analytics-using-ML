# HR-Analytics-using-ML

Attrition is a problem that impacts all businesses, irrespective of geography, industry and size of the company. It is a major problem to an organization, and predicting turnover is at the forefront of the needs of Human Resources (HR) in many organizations. Organizations face huge costs resulting from employee turnover. With advances in machine learning and data science, it’s possible to predict the employee attrition and we will predict using Random Forest Classifier (with accuracy rate 90%).


Step I) EDA ( Exploratory Data Analysis ) 
1. Analysis on categorical (object column) column w.r.t. Target column.
Here Target column = Attrition
Categorical column like Business Travel, Department,  Education,  Gender, Overtime,  Job Role.

2. Analysis on continuous (number column) Data w.r.t. Target column like Age, Income, Distance From Home, Year At Company, Daily Rate.

3. Analysis on Discrete Data w.r.t. Target column like Environment, Job Satisfaction, Work Life Balance.

Step II) DATA PRE-PROCESSING 
1. Finding null values. (There is no null values)
2. Handling categorical data.
3. Dropping unnecessary data.

Step III) MODEL CREATION 
Use train-test-split from sklearn model.
75% data for training and remaining 25% for testing.
Apply two Machine Learning Classifier.
1. Decison Tree Classifier with accuracy rate 84% 
2. Random forest Classifier with accuracy rate 90% 


