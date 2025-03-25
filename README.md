# Electronics_Store_Sales_Analysis 

### Stack
![Static Badge](https://img.shields.io/badge/Power_BI-%2376B900?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/Microsoft_Excel-%23D40000?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/Power_Query-%231C9AD6?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/Python-%23FAD83B?style=for-the-badge&logo=python)


## Background & Overview

This [interactive] project provides an in-depth analysis of the **Canadian job market** trends for data-related roles. The dataset, collected from **Glassdoor**, includes job postings from **January 1–31, 2025**, covering six key roles: 

Data Analysis Stack:  
The analysis utilizes **Power Query** for data extraction and transformation and **Excel** for visualization through an **interactive** dashboard.  
For this analysis I used the following apps to perform the following tasks:  
Microsoft Power BI:   
Microsoft Excel:  
Power Query Editor:   
Python: used to generate the factitious dataset  


## Data Structure Overview 

I also created custom SQL queries to access the centralised Azure database from outside the Power BI environment. Using Python and OOP principles, I built a DatabaseConnector class to automate custom SQL queries when needed.

NOTE: the data presented here is from a fictitious company and has been fabricated. It is NOT sensitive data from real customers.

I created a fictitious company and generated all the required data files for this analysis using Python.

## Executive Summary

This project analyzes sales data from an electronics store to identify key trends, customer behavior, and product performance. It includes data cleaning, exploratory data analysis (EDA), and visualization using Excel and Python. The project also features an interactive dashboard to showcase insights such as revenue trends, top-selling products, and regional sales distribution. This analysis demonstrates fundamental data analytics skills, including data manipulation, visualization, and business insights generation, making it suitable for portfolio presentation.

Using Microsoft Power BI and Power Query Editor, I pulled data from 6 different sources (including Azure Cloud) and created a relational database model and a Microsoft Power BI report to monitor sales performance across the organisation. The 4-page report is interactive and filterable, and uses historical data from 2010-2023 sales to track relevant KPIs and forecast their performance in the near future.


### Star Schema Data Model for Sales and Returns Analysis 

![STAR-Schema data model](https://github.com/user-attachments/assets/4a5b3d97-c3c4-4046-b06f-0f118ec7f589)

This **Star Schema Data Model** is designed to support **sales and return data analysis** in **Power BI**. The model follows a **fact-dimension structure**, optimizing performance and query efficiency.  

#### **Key Components:**  
- **Fact Tables:**  
  - **Sales Data:** Contains transaction details such as order date, order quantity, and customer & product references.  
  - **Return Data:** Tracks product returns, including return date and quantity.  

- **Dimension Tables:**  
  - **Customers Lookup:** Stores customer demographics (e.g., income, gender, education).  
  - **Product Lookup:** Provides product details, linked to **Product Categories Lookup**.  
  - **Calendar Lookup:** Supports time-based analysis (e.g., month, quarter, year).  
  - **City & Province Lookup:** Enables geographic segmentation.  

This model ensures **efficient data relationships** for generating **insights on sales trends, customer behavior, and return rates**.  



