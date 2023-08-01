# Telco Customer Churn Analysis 
![Telcom analysis](https://github.com/Jenonah/Telco-customer-churn-report/assets/138598218/54630d43-09e1-4f33-902c-5451bc3ef4f2)

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
# Findings
After conducting the analysis, the following key findings have emerged:

1. The Telco company has a total of 7,043 customers, with 1,869 customers being churned and 5,174 customers retained.

2. The company offers services in eight different categories, with a total of 26,780 services provided so far.

3. Among the churned customers, 143 customers subscribed to only one category. Additionally, 16 churned customers had subscribed to all eight categories, suggesting other factors contributing to their decision to churn.

4. In terms of payment methods, the electronic check was the most frequently used, accounting for a total of 2,365 payments (1,071 by churned customers and 1,294 by retained customers).

5. Analyzing the top five customers with the highest total charges revealed that the top-ranked customer was a churned customer, while the remaining four were retained customers. Similarly, when examining monthly charges, the top four customers were retained customers, while the least of the five was a churned customer.

6. Tenure was grouped into 10s, with the 0-9 tenure category having the highest number of customers at 1,854 (931 retained and 923 churned). On the other hand, the 30-39 tenure category had the lowest number of customers, with 653 in total (144 churned and 509 retained).

Based on these findings, it is evident that the available data is insufficient to determine the exact causes of customer churn. Further analysis and exploration are required to identify the potential factors contributing to churn in order to develop effective strategies for customer retention.

----
# Recommendation
Based on the findings from the analysis, the following recommendations can be made

1. Customer Retention Strategies: Since a significant number of customers are churning despite subscribing to multiple categories of services, it suggests that there may be other underlying factors influencing their decision to leave. The company should conduct additional research, such as customer surveys or feedback analysis, to identify these factors and implement targeted strategies to improve customer retention.

2. Service Enhancement: While 143 churned customers subscribed to only one category of service, this indicates a potential area for improvement. The Telco company should focus on enhancing the quality and value proposition of these specific services to increase customer satisfaction and reduce churn

3. Further explore factors influencing customer churn: While the available data was insufficient to determine the exact causes of customer churn, it is crucial to conduct additional research, gather more customer feedback, and perform in-depth analysis to identify the underlying factors contributing to churn. This can involve qualitative surveys, customer interviews, and segmentation analysis to gain a deeper understanding of customer behavior, preferences, and pain points.

