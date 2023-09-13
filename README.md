# EDA-ON-TELECOM-COMPANY

INTRODUCTION:
The objective of this research project is to estimate customer attrition and investigate demographic differences between clients who have churned and those who have not, with the aim of analysing customer turnover within a telecommunications company.

Project Overview: Customer attrition is a significant concern for telecommunications companies, and mitigating it requires the development of predictive models and an understanding of the influencing factors. This project employs machine learning techniques to compare the demographic attributes of churned customers with those who have remained loyal.

Dataset: The project utilises the telecom Customer Turnover dataset, which comprises information about the clients’ demographic characteristics, subscribed services, and turnover rates. The dataset is available in CSV format within the data directory.

Methodology: By delving into historical data, identifying patterns, and employing various statistical methodologies, we will harness machine learning to pinpoint the customers most prone to churning. This article will delve into the utilisation of customer data and behavioural traits to construct a classification model capable of predicting customer attrition.

Project Description: Customer churn, in essence, signifies the number of customers discontinuing their engagement with a company within a defined time frame. It quantifies how frequently customers cease using a company’s offerings. Churn can arise from various factors such as dissatisfaction with the product or service, the presence of competitive alternatives, shifts in consumer preferences, or external influences. It is imperative for businesses to comprehend and manage customer attrition, as it can profoundly impact sales, growth, and overall customer satisfaction. In this project, we will assess the probability of a customer departing from the company, identify key churn indicators, and explore strategies for retaining customers to mitigate this challenge.

Objective: The primary goal is to conduct a comparative analysis of the demographic characteristics of churned and non-churned customers, presenting the results through visualisations, including stacked bar charts and gain insights into factors influencing customer churn.

Handling Missing Values and Data Types:
The dataset comprises of 21 columns and encompasses 7043 observations. Although no apparent missing values are evident in the data collection, we did observe that the column named “TotalCharges” had been incorrectly identified as an object data type. This column inherently represents a numerical variable, as it quantifies the total expenses incurred by customers. To facilitate further analysis, we deemed it necessary to convert this column into a numeric data type. This transformation was executed using the pd.to_numeric function. By default, this function raises an exception when it encounters non-numeric data. Nevertheless, we overcame this by specifying the “errors=’coerce’” argument, which enabled us to substitute non-numeric instances with Nan values.

Insights from the Plots:
1.	The churn rate is significantly elevated among senior citizens compared to non-senior customers.
2.	Customers with month-to-month contracts exhibit a substantially higher churn rate in contrast to those with different contract durations.
3.	There is a moderately higher churn rate among customers who do not have partners.
4.	The churn rate is notably higher for customers without children.
5.	The payment method “electronic check” displays a significantly elevated churn rate when compared to other payment methods.
6.	Customers with InternetService including fiber optic as part of their contract experience a notably higher churn rate.
