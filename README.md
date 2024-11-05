  # LITA_Capstone_project

### Project Title : SalesData Analysis And CustomerData Analysis
 
### OUTLINE:

[Project Overview](#project-overview)

[Data Sources](#data-sources)

 
[Tools Used](#tools-used)


[Data Cleaning and Preparations](#data-cleaning-preparation)


[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)


[Data Visualization](#data-visualization)




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


CustomerData Overview


![CustomerData 1](https://github.com/user-attachments/assets/79513122-8d5e-4079-af14-a48d8496c32b)



![CustomerData 2](https://github.com/user-attachments/assets/5c604e02-84e0-4373-8dc2-c566da07cad5)
