
# Introduction

A classifier model is used to predict whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company. There are a total of 21 different features including the target variable, churn. Churn provides the information of whether or not a customer has stopped doing business with the company. 

A random forest algorithm will be used to categorize all the features to predict the target variable. The feature importance will tell us how many times a feature is used to decide whether or not a customer is more likley to churn. The 21 features in this dataset are listed below:

- state  
- account length
- area code 
- phone number
- international plan
- voicemail plan
- number vmail messages
- customer service calls
- total intl minutes/calls/charge
- total day minutes/calls/charge
- total eve minutes/calls/charge
- total night minutes/calls/charge
- churn (target variable)

RandomizedSearchCV is an algorithm used to find the best combination of parameters in the model to increase the accuracy of the random forest method in making predictions.

All the imports and functions used in this project are imported below: 




# Conclusion


The tuned model was able to provide a more accurate prediction. Therefore three insights/recommendations are listed below:

1. Customers who use more minutes during the day and get charged are more likely to stop doing business. Therefore looking into lowering the usage total during the day charge.

2. Customers that have a voice mail set up are more likely to continue business. Assist customers with setting up a voicemail may decrease the churn rate.

3. Customers who have an international plan are more likely to discontinue doing business.

