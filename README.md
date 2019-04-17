# DS-Examples-using-R-
DS Examples using R 
This article gives you step by step procedure to connect to SAP HANA DB and do the analytics
1.Install HANA Client tools, R studio
2.Request for READ access to HANA Data Base
3.Setup the Data source using HDBODBC driver (with the SAP HANA DB Server details)
4.Download the RODBC package in your R Studio
5.Establish the database connection using R commands
6.Execute SQL Query function using SQL commands on R.
7.Feed the data to the required algorithms to analyze the data/results

This example shows how to fetch product wise Invoice to explore the Market Basket analysis

Market Basket Analysis is one of the key techniques used by large retailers to uncover associations between items. It works by looking for combinations of items that occur together frequently in transactions. To put it another way, it allows retailers to identify relationships between the items that people buy. Market Basket Analysis (MBA) which uses Association Rule Mining on the given transaction data.

An example of Association Rules
Assume there are 100 customers
* 10 of them bought milk, 8 bought butter and 6 bought both of them
*Who bought milk => bought butter
* support = P(Milk & Butter) = 6/100 = 0.06
* confidence = support/P(Butter) = 0.06/0.08 = 0.75
* lift = confidence/P(Milk) = 0.75/0.10 = 7.5

Use cases / Benefits:
Store layout
Marketing , promotions
Website content placement
Recommended engine
Cross selling


