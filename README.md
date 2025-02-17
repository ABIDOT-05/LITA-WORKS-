# LITA-WORKS
## project title : Product Sales Analysis
-----------------------------------------

[project overview](#project-overview)

 [Data sources](#data-sources)

 [Tools Used](#tools-used)

 [Data Cleaning and preparation](#data-cleaning-and-preparation)

 [Exploratory Data Analysis](#exploratory-data-analysis)

  [Data Analysis](#data-analysis)

[ Data Visualization](#data-visualization)


### project overview
This project  aims to provide insights that drive strategic decicision making through comprehensive reports and dashboards. It includes columns such as 
- Region
- line of business
- Market
- revenue
- units sold
This columns provide the needed information to analayze the data properly,spot trends, report accurately and tell the right story 

### Data sources
The primary source of this data is Salsdata.xslx. the data can also be downloaded from open sources online and online data repositories such as kaggle. 

### Tools Used
- Microsoft Excel for : 

1.  data cleaning
2.  data analysis 
3.  data visualization

- SQL - Structured Query Language for data query

- Github for Portfolio

### Data Cleaning and preparation

  - dta handling and inspection
  - dealing with duplicate values
  - deleting empty rows and misiing values
  - Data cleaning and formatting

  ### Exploratory Data Analysis 
  -----------------------------
  This involves exploring the Data to answer some questions about it such as 

  - How does revenue vary across different regions?
  - What are the top-performing markets in terms of revenue and units sold?
  - Which stores generate the highest revenue?
  - Which models are most popular in terms of revenue and units sold, and how do they perform across different regions?

    ### Data Analysis

    ```SQL
    create database lita_db
    create table sales(
    region varchar(max),
    Region varchar (max),
    Market varchar (max),
  	Store varchar (max),
  	Trade_Date date,
    Fiscal_Period date ,
    Model varchar (max),
    Line _Of_Business (max),
    Day varchar (50),
    Category varchar (max),
    Revenue bigint,
    Units_Sold int
    )
    ```
    ...
    ...
    
    ```SQL
    SELECT * FROM sales
    ```

    ### Data Visualization

    ![image](https://github.com/user-attachments/assets/589ecbd3-5322-4b91-a4f4-3644dcc44488)
    ![image](https://github.com/user-attachments/assets/43ca5648-e004-4dbf-bd5a-2ba7706a5efc)
   ![image](https://github.com/user-attachments/assets/32d83edc-a239-4fc3-a276-0a06bb7a2455)




