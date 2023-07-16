# Telco Customer Churn Analysis 
----
# Objectives
To analyze customer churn, identify the factors contributing to churn, and explore potential strategies to reduce churn.
---
# Data Sourcing
From Kaggle https://www.kaggle.com/datasets/blastchar/telco-customer-churn/download?datasetVersionNumber=1

----
# Data Cleaning
To clean the data using Power Query Editor, I followed several steps. Firstly, I edited the column headers to create spaces between words for better readability and clarity. 
Next, I created a conditional column called "Customer Status" based on the values in the "Churn" column. This new column helped to reveal the customer status as either "Churned" or "Retained," providing valuable insights into customer status.
To determine the total number of services received per customer, I created example columns for each service column. For instance, if a particular service was marked as "Yes," I assigned a value of 1, and for "No" or "No Phone," I assigned a value of 0. This conversion allowed me to quantify the services received by each customer
Finally, I used a custom function to calculate the total services per customer. This function summed up the values from the example columns created earlier, giving an accurate count of the total services received by each customer.
----
# Findings and Recommendataion
