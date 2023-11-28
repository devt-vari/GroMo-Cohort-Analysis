# GroMo-Cohort-Analysis

**Customer Purchase Trend and Retention** 

# **Overview of the case study**

The case study contains 2 data sets (Customer data and Orders Data).

- Data Set 1 - Customer Data

[Case_Study_Customer_Data.csv](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8c082a5b-1ccf-4d30-b109-964fd558af03/Case_Study_Customer_Data.csv)

- Data Set 2 - Orders Data

[Case_Study_Orders_Data.csv](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c4210874-6006-4860-841b-182c61254d03/Case_Study_Orders_Data.csv)

> *Note- Date column might require data cleaning. Feel free to create new columns with clean data.*
> 

Customer data contains a list of all NEW customers acquired during the period of 1-Jan-2021 to 30-Jun-2021 along with their 

- customer ID (**Cust ID**),
- date customer registered on app (**Customer Created Date**),
- week of registering (**Week**),
- customer profession group (**Cust Profession**).

While, Orders Data contains a list of all purchase orders till date (**Order No**), created by customers acquired during the period of 1-Jan-2021 to 10-Sep-2021 along with 

- customer ID (**Cust ID**),
- Order created date (**Order Date**) .
- Final Status of the Order (**Order Status**) When a customer creates a purchase order, it may or may not eventually be purchased. When a purchase order is purchased, it is marked as ‘Won’ (in column **Order Status**) and
- Order value in INR (**Order Amount**).

**Note**: Revenue is counted only when the order is marked as ‘Won’ else it's a lost opportunity. Some cases where Order Amount is blank or Order Status is ‘Other’ are to be considered as 0 revenue.

# **Objective**

1. Prepare analysis on the Orders Data and Customer Data while touching upon monthly revenues, users, monthly revenue per user etc
2. Prepare an analysis showing how many users placed a Purchase order, while how many actually converted bifurcated by
    - Month
    - Customer Profession
3. Prepare a COHORT analysis showing the purchase pattern of users by month
    1. Cohort Analysis: Cohort analysis is a type of analysis where we understand the behavior of customers by groups over a period of time. Eg. How are the customers who joined in the month of Jan 2021 are performing in the coming months in terms of # of orders placed, # of purchases made etc

