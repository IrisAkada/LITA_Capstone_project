  # LITA_Capstone_project

### Project Title : CustomerData Analysis
 
### OUTLINE:

[Project Overview](#project-overview)

[Data Sources](#data-sources)

 
[Tools Used](#tools-used)


[Data Cleaning and Preparations](#data-cleaning-preparation)


[Exploratory Data Analysis](#exploratory-data-analysis)


[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)


### Project Overview
This Data Analysis Project aims at Providing insight into the sales performance of Customerdata over the past two years.
By Analyzing the various parameters in the data received we seek to gather enough insight to make inform decisions which will enable us to tell compelling stories around our data from the insight gotten and the best performance from our project.


### Data Sources 
The Source of the data used here is CustomerData Sales.xlsx provided by The Incubator Hub for our capstone project. 


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


```select product, sum(Total_sales) as TotalRevenue from [dbo].[LITA Capstone Dataset csv]
where product in ('Hat','shoes','Gloves','socks','Jacket','shirt')
group by Product
order by TotalRevenue desc```


### Data Visualization

