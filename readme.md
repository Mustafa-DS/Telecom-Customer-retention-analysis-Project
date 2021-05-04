# Telecom Customer Exploration

## Dataset

The data consisted of Churn and attributes of approximately 7000 Telecom customers. The attributes included (gender','SeniorCitizen','Partner','Dependents','tenure','MultipleLines','InternetService','OnlineSecurity','OnlineBackup','DeviceProtection','TechSupport','StreamingTV','StreamingMovies', 'Contract', 'PaperlessBilling','PaymentMethod', 'MonthlyCharges', 'TotalCharges', 'Churn'), Most variables are categorical (Yes or No), Only both Charges and Tenure are numeric in nature.
The dataset can be found on Kaggle's site here with it's features explained also
 [here]
(https://www.kaggle.com/blastchar/telco-customer-churn),

## Summary of Findings

1.I found a strong relation between Monthly Charges and Churn where the more the charges decrease the
more likely the customer is going to stay and vice versa.
2.I also found a relation between Tenure ( Lenght of Subscription ) and the Churn, The longer the Tenure
thr more likely the Customer is going to stay with an interseting exception as among the longest subscribed 
customers have a noticable portion of unsubscribing too.
3. Having a senior citizenship probability of Churn is not being much by Monthly Charges, But among those who haven't
(The Majority) the key relation of Monthly charges-Churn is applied well.
4. Most Unsubscribers have a Monthly Contract, Those with 1,2 years Contracts tends to stay only the Charges would 
affect their decision.


## Key Insights for Presentation

For the presentation, 
I focus on just the influence Monthly Charges and Tenure
I start by introducing the
Churn variable, followed by the Tenure and Monthly Charges distribution.

Afterwards, 
I introduce each of the categorical variables one by one. To start,
I use the count plot of Churn over Contract Type.
Then, i used violin plot to view relation of Tenure and Monthly Charges
over Churn.
Also after that used Barplots to introduce Contrat Over Monthly Charges and Churn 
and Contrat Over Tenure and Churn to get more deeper in my analysis.
i used different color palettes for each quality variable to make sure it
is clear that they're different between plots.