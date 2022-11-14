# Customer-Churn-Prediction

## Description
A notable cause of organization profit loss is the rate at which customers churn or leave the organization. Customer churn, also known as customer attrition refers to the rate at which a proportion of an organizations customers decide to stop using a company's product or service within a particular period of time. This analysis sought to analyse data on the churn decisions of customers subscribed to a telecommunication network and predict the likelihood of customers churning.

## Data Understanding
The data for this project is in a csv format. The following describes the columns present in the data.

Gender -- Whether the customer is a male or a female

SeniorCitizen -- Whether a customer is a senior citizen or not

Partner -- Whether the customer has a partner or not (Yes, No)

Dependents -- Whether the customer has dependents or not (Yes, No)

Tenure -- Number of months the customer has stayed with the company

Phone Service -- Whether the customer has a phone service or not (Yes, No)

MultipleLines -- Whether the customer has multiple lines or not

InternetService -- Customer's internet service provider (DSL, Fiber Optic, No)

OnlineSecurity -- Whether the customer has online security or not (Yes, No, No Internet)

OnlineBackup -- Whether the customer has online backup or not (Yes, No, No Internet)

DeviceProtection -- Whether the customer has device protection or not (Yes, No, No internet service)

TechSupport -- Whether the customer has tech support or not (Yes, No, No internet)

StreamingTV -- Whether the customer has streaming TV or not (Yes, No, No internet service)

StreamingMovies -- Whether the customer has streaming movies or not (Yes, No, No Internet service)

Contract -- The contract term of the customer (Month-to-Month, One year, Two year)

PaperlessBilling -- Whether the customer has paperless billing or not (Yes, No)

Payment Method -- The customer's payment method (Electronic check, mailed check, Bank transfer(automatic), Credit card(automatic))

MonthlyCharges -- The amount charged to the customer monthly

TotalCharges -- The total amount charged to the customer

Churn -- Whether the customer churned or not (Yes or No)

## Summary of Data Analysis Methods
Firstly, the dataset was viewed in microsoft excel to have an understanding of the nature of the data and understand how the cleaning was to be done. .The datasets were loaded into Jupyter Notebook where the data values and types where checked. Also, null values and missing values were dealt with at the data cleaning stage and all unwanted columns dropped. This was done to ensure that the ML models were not obstructed from makig accurate predictions. Appropirate visualizations were applied to understand the relationships between the variables. Also, various models were trained to make predictions on the data set and to determine the most suitable model to be tuned for further prediction.


## Hypothesis and Questions
***Hypothesis***
1. Male users are more likely to churn if services are not satisfactory, as compared to females
2. Users of fibre optics are less likely to churn as compared  to DSL
3. Security measures(backups, online security, device protection,tech support) result in a low number of churn
4. The availability of the streaming services negatively affects churn rates
5. Long term contracts result in low churn out rates.
6. utilizing paperless billing reduces churnout rate
7. Users of credit cards & bank transfers have a low churn out compared to the others.
8. Customers are less likely to churn after the 10th month, regardless of price.

***Questions***
1. Are male users are churning out more than female users?
2. Are users of fibre optics less likely to churn as compared  to DSL?
3. Does access to security measures(backups, online security, device protection,tech support) result in a low churn rate?
4. Does the availability of the streaming services negatively affects churn rates?
5. Does long term contracts result in low churn out rates?
6. Does utilizing paperless billing reduces churnout rate?
7. Does users of credit cards & bank transfers have a low churn out compared to the others?
8. Are customers churning less after the 10th month regardless of the total price?

# Conclusion
Based on the prediction outcomes, it can be suggested that given the same period of time, the telecommunicaition company is liely to lose more customers if the preferred services are not provided to the customers.
