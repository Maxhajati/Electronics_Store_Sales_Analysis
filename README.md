# Electronics Store Sales Analysis 

![0 2nd Dashboard](https://github.com/user-attachments/assets/07d3790d-4a96-451c-a50f-f3bd52d7cbc6)

## Background & Overview
Designed for data-driven analysis, this **Sales Dashboard** presents key business metrics for a fictional electronics store, **Electromart**.
The dataset, generated using **Python**, represents Electromart’s business data across the 2023–2024 time frame and includes:  
- 💰 **Sales Data**: Transactions capturing product sales  
- 🔄 **Return Data**: Records of returned items  
- 🧑‍💼 **Customer Information**: Demographic and purchasing details  
- 📦 **Product Details**: Information on available products, pricing, and categories  
- 🌍 **Territory Lookup**: Regional and city-level sales data   

This project analyzes sales data from an electronics store to identify key trends, customer behavior, and product performance. It includes data cleaning, exploratory data analysis (EDA), and visualization using Excel and Python. The project also features an interactive dashboard to showcase insights such as revenue trends, top-selling products, and regional sales distribution. This analysis demonstrates fundamental data analytics skills, including data manipulation, visualization, and business insights generation, making it suitable for portfolio presentation.

## Data Analysis Stack  
To develop this **interactive** dashboard, a series of powerful tools is leveraged, ensuring seamless data processing, analysis, and visualization.
<p>
  <img src="https://img.shields.io/badge/Power%20BI-%23F2C811?style=for-the-badge&logo=power-bi&logoColor=black" />
  <img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/Power%20Query-385E9D?style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</p>


## Data Model Overview 
To generate the required data for analysis, a fictitious company with synthetic customer names was created using **Python**. To support sales and return data analysis in Power BI, a **Star Schema Data Model** was designed. This model follows a fact-dimension structure, ensuring optimized performance and efficient querying.


#### **Key Components:**  
- **Fact Tables:**  
  - **Sales Data:** Contains transaction details such as order date, order quantity, and customer & product references.  
  - **Return Data:** Tracks product returns, including return date and quantity.  

- **Dimension Tables:**  
  - **Customers Lookup:** Stores customer demographics (e.g., income, gender, education).  
  - **Product Lookup:** Provides product details, linked to **Product Categories Lookup**.  
  - **Calendar Lookup:** Supports time-based analysis (e.g., month, quarter, year).  
  - **City & Province Lookup:** Enables geographic segmentation.  

This model ensures **efficient data relationships** for generating insights on sales trends, customer behavior, and return rates.  

![STAR-Schema data model](https://github.com/user-attachments/assets/4a5b3d97-c3c4-4046-b06f-0f118ec7f589)


## Executive Summary

Using Microsoft Power BI and Power Query Editor, I pulled data from 6 different sources (including Azure Cloud) and created a relational database model and a Microsoft Power BI report to monitor sales performance across the organisation. The 4-page report is interactive and filterable, and uses historical data from 2010-2023 sales to track relevant KPIs and forecast their performance in the near future.

## Power BI Report Preview
This interactive and comprehensive Power BI report contains four pages, including an Executive Summary, a Customer Detail Page, a Product Detail Page and a Stores Map.





