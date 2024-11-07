  # LITA_Capstone_project

### Project Title : SalesData Analysis And CustomerData Analysis
 
### OUTLINE:

[Project Overview](#project-overview)

[Data Sources](#data-sources)

 
[Tools Used](#tools-used)


[Data Cleaning and Preparations](#data-cleaning-preparations)


[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)


[Data Visualization](#data-visualization)

[Data presentation](#data-presentation)







### Project Overview
This Data Analysis Project aims at Providing insight into the sales performance of Salesdata over the past two years.
By Analyzing the various parameters in the data received we seek to gather enough insight to make inform decisions which will enable us to tell compelling stories around our data from the insight gotten and the best performance from our project.


### Data Sources 
The Source of the data used here is LITA_Capstone_Dataset xlsx provided by The Incubator Hub/ LADIES IN TECH AFRICA for our capstone project. 


### Tools Used
- Microsoft Excel [Download here](https://www.microsoft.com
  
  1.For Data Analysis
 
  2.For Data Visualization

- SQL Structured Query language for querying the Data 
- Microsoft Power BI for DAX expressions and Data Visualization

### Data Cleaning and Preparations
In the initial phase of the Data cleaning and preparations, we perform the below actions;
1. Data loading and inspection
2. Data cleaning and formatting

### Exploratory Data Analysis
 EDA involves the exploring of the Data to answer some questions about the data such as;
 - what is the total Number of sales for each Product
 - What is the Monthly Sales total for the current year
 - What is the top selling Product
 - What is the total Revenue for each product and regional breakdown?



### Data Analysis
This is where we displayed some basic lines of sql code or queries and some DAX expressions used during the analysis

```SQL
select product, sum(Total_sales) as TotalRevenue from [dbo].[LITA Capstone Dataset csv]
where product in ('Hat','shoes','Gloves','socks','Jacket','shirt')
group by Product
order by TotalRevenue desc
```

### Data Visualization

SalesData Overview


![SalesData 1](https://github.com/user-attachments/assets/1a823f47-ad22-4093-86d5-899ddddc46a8)


![SalesData 2](https://github.com/user-attachments/assets/2248dba7-41f0-42b7-932b-cb7088c19edd)


![SalesData 3](https://github.com/user-attachments/assets/e62773c5-cace-4dc6-8848-a18911592096)

### Data presentation

This is a project report of a salesdata of a retail store, total quantity of 345,000,00 of the below listed product: Shoes, Gloves, Hat, Jacket, Shirt. This project is aimed at analyzing and evaluating the sales performance of each products in regions and the revenue generated monthly as this will help draw satisfying recommendations and conclusion in making a data informed decisions on the business.

From the Dashboard 1 of SalesData above,A total number of 170,000 products (summation of all the product sold) in the regions with the sum total unitprice of 1million summing up the totalsales revenue of 11Million.
The breakdown of sales analysis for each product  using table tool revealed the performance of each product as follows;
 - Shoes: 3,087,500
 - Shirt: 2,450,000
 - Hat : 1,587,5000
 - Gloves : 1,500,000
 - Jacket: 1,050,000
 - Socks : 912,500
summing up the total revenue of 10,587,500 approximately 11million.

Product performance in each of the region using card tools and filter rating it on a scale of 100% in the regions  revealed the result as follows.
 - Gloves:16.67% was sold in the west
          83.33% was sold in the south

 - Hat: 11.02% was sold in the North
        33.86% was sold in the East
        55.12% was sold in the West

 - Jacket:50% was sold in the North
          50% was sold in the East

 - Shirt: 48.98% was sold in the East
          51.02% was sold in the North

 - Shoes: 6.07% was sold in the East
          4.86% was sold in the West
          89.07% was sold in the South

 - Socks: 26.03% was sold in the South
          73.93 was sold in the West.

In Summary the analysis established shoes as the top performing product, having the highest revenue of 3million amongst the other products summing up 11million.
The most active Region is the South and the passive region is the West. The findings also revealed that each of the product were mostly sold in two or three of the regions and no product had sales in all of the  four regions.

### CustomerData Dashboard


![CustomerData 1](https://github.com/user-attachments/assets/79513122-8d5e-4079-af14-a48d8496c32b)



![CustomerData 2](https://github.com/user-attachments/assets/5c604e02-84e0-4373-8dc2-c566da07cad5)


### CustomerData Report Dashboard.
The exploratory Data analysis performed on this dataset using cards,charts, Table revealed the Total Revenue from the monthly subscription in two years is 150million, total sales value of 262million and total Number of 75,ooo,oo Customers in all the regions. The total number of subscription is 131,000,00 and the total number of cancelled subscription is 34,000.

Breakdown of analysis revealed the active subscription types as follows: Basic, standard and premium.
11.3% of customers in the north canceled their Standard subscription, 33.33% of customers canceled their premium subscription in the South and 33.33% canceled their Basic subscription in the west.

Chart 2, revealed the total count of subscription by region.

 1.North 19,000,00 
 
 2.South 38,000,00
 
 3.East 19,000,00
 
 4.West 56,000,00
 

Table 1 and 2 revealed the performance of the regions in year 2023 and 2024 subscriptionstart and subscriptionend.
Year 2023 subscriptionstart generating sum total89,902,969 and 59,916717 in 2024.
Table 2 revealed the sum total 89,902,969 as revenue in 2023 and 59,916,717 as revenue in year 2024.

In summary the analysis revealed Basic subscription type as the most preferred subscription type with the total revenue of 75million , in regions the East had no subscription canceled.
Further analysis revealed the North, South, West canceled their subscription with no renewal.                                                                                                                                                                         


