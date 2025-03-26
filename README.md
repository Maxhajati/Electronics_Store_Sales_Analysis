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

Using Microsoft Power BI and Power Query Editor, I pulled data from 6 different sources (including Azure Cloud) and created a relational database model and a Microsoft Power BI report to monitor sales performance across the organisation. The 4-page report is interactive and filterable, and uses historical data from 2010-2023 sales to track relevant KPIs and forecast their performance in the near future.

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


## 📊 Electromart Sales Report – Executive Summary  

![1 Executive Summary](https://github.com/user-attachments/assets/b3c4bedb-c72e-4c30-a2d4-f0b026a11986)
 
This Sales Report provides a high-level summary of key sales metrics, including **total revenue, profit, and order trends**. The report visualizes performance across different timeframes and locations, helping stakeholders track business growth and identify areas for improvement.  

## 🔑 Key Highlights  
- **Total Revenue:** **$9.7M**  
- **Total Profit:** **$3.0M**  
- **Total Orders:** **50.7K**  

### 📉 Monthly Performance  
- **Monthly Revenue:** **$0.56M** *(Down 10.43% from last month: $0.62M)*  
- **Monthly Profit:** **$174.5K** *(Down 9.69% from last month: $193.2K)*  
- **Monthly Orders:** **3,000** *(Decreased 220 from last month: -6.83%)*  

### 📍 Sales & Profit Distribution  
- **Orders by Province:**  
  - Ontario: **58% (23.8K orders)**  
  - Quebec: **30.5% (12.5K orders)**  
  - Alberta: **11.5% (4.7K orders)**  
- **Profit by Province:**  
  - Ontario: **$0.99M (58.0%)**  
  - Quebec: **$0.51M (29.6%)**  
  - British Columbia: **$0.21M (12.4%)**  

### 📊 Product Performance  
- **Top-Selling Categories:**  
  - Accessories: **20.4K orders**  
  - Headsets: **10.6K orders**  
  - Storage: **6.7K orders**  
  - Monitors: **6.4K orders**  
  - Webcams, Printers, Microphones follow behind  

### 📈 Revenue Trend  
The **revenue trend chart** shows steady growth since early 2023, with notable fluctuations but an overall upward trajectory.  

----------

# 📊 Electromart Sales Report – Customer Report  

This **Customer Report** provides insights into the **customer base, purchasing trends, and top customers**. It highlights customer segmentation by **income level and occupation**, tracks order trends over time, and identifies the highest-revenue customers.  

## 🔑 Key Highlights  
- **Total Customers:** **8.98K**  

### 📉 Customer Segmentation by Income Level and Occupation
  - High-income customers contribute the majority of orders (63.3%), followed by average (22.5%) and low-income (14.2%) groups.
  - Technicians (38.2%) and salespersons (37.9%) are the dominant buyer segments, with clerks making up 23.9% of orders.


### 📈 Customer Order Trends  
The **customer order trend chart** shows a steady increase in orders over time, with notable growth in **late 2023 and early 2024**.  

### 🏆 Top Customers by Revenue  
- **Mr. Joseph Bates** is the highest-grossing customer, generating $9.13K from 35 orders.
- Several other customers, including Mrs. Kristy Morrison ($6.12K) and Mr. Andrew Jones ($6.32K), also contribute significantly.

---

# 📍 Electromart Sales Report – Product Report  



---

# 📍 Electromart Sales Report – Territory Report  

This **Territory Report** provides insights into **total orders by city and province**, highlighting key geographical regions driving sales. A **map visualization** further illustrates order distribution across Canada.  

## 🔑 Key Highlights  
- **Top Province by Orders:** **Ontario (23.8K orders)**  
- **Top City by Orders:** **Toronto (16.8K orders)**  

### 📊 Total Orders by Province  
- **Ontario:** **23.8K orders**  
- **Quebec:** **12.5K orders**  
- **Alberta:** **4.7K orders**  
- **British Columbia:** **4.6K orders**  
- **Manitoba:** **2.0K orders**  
- **Nova Scotia:** **1.5K orders**  
- **Other Provinces:** Small order contributions from Saskatchewan, Newfoundland, New Brunswick, and Prince Edward Island.  

### 🌆 Total Orders by City  
- **Toronto:** **16.8K orders**  
- **Montreal:** **8.4K orders**  
- **Vancouver:** **3.6K orders**  
- **Ottawa:** **2.7K orders**  
- **Calgary:** **2.5K orders**  
- **Other Cities:** Edmonton, Hamilton, Quebec City, Winnipeg, London, Halifax, and Windsor all contribute over **1K orders** each.  

### 🗺️ Geographic Insights  
The **territory map visualization** highlights major sales hotspots, with **Ontario and Quebec dominating**. **Toronto, Montreal, and Vancouver** stand out as the top cities contributing to total orders.  

---


# 📢 **Business Recommendations for Electromart**  

Based on the **Executive, Customer, Product, and Territory Reports**, here are **key recommendations** to drive growth, improve efficiency, and maximize profitability for **Electromart**.  

---

## **1️⃣ Revenue Growth Strategies**  
✅ **Expand High-Performing Product Categories**  
- **Accessories & Headsets** dominate total orders. Increase inventory and marketing efforts for these categories.  
- Explore **bundling deals** to boost sales of **Storage, Monitors, and Webcams**, which show moderate demand.  

✅ **Increase Regional Sales Efforts**  
- **Ontario & Quebec** contribute the most orders (58% of total sales). Strengthen marketing and fulfillment capabilities here.  
- **Alberta & British Columbia** show potential growth. Invest in regional campaigns to drive demand.  

✅ **Leverage High-Value Customers**  
- **Mr. Joseph Bates & other top customers** contribute significant revenue. Implement a **VIP loyalty program** to retain and reward them.  
- Offer **exclusive discounts or early access** to new products for frequent buyers.  

✅ **Boost Seasonal Sales**  
- The **revenue trend shows fluctuations**. Identify peak sales periods and plan **seasonal promotions** accordingly.  
- Utilize **Black Friday, Back-to-School, and Holiday campaigns** to increase sales.  

---

## **2️⃣ Operational Improvements**  
✅ **Optimize Inventory Management**  
- **Align stock levels with demand trends** (e.g., prioritize Accessories, Headsets, and Storage).  
- Implement **AI-based demand forecasting** to prevent overstocking or shortages.  

✅ **Improve Order Fulfillment & Logistics**  
- Since **most orders come from Ontario, Quebec, and Alberta**, optimize warehouse locations for **faster delivery**.  
- Partner with local couriers for **same-day or next-day delivery options** in major cities.  

✅ **Enhance Customer Support & Retention**  
- Provide **personalized customer support** for high-value buyers.  
- Introduce a **live chat feature** to assist customers with product inquiries in real time.  

---

## **3️⃣ Marketing & Customer Engagement**  
✅ **Target High-Income & Technician Segments**  
- The **majority of orders come from high-income customers (63%) and Technicians (38%)**.  
- Develop **targeted ad campaigns** for these segments, focusing on **premium features & professional-use cases**.  

✅ **Leverage Digital & Social Media Advertising**  
- Use **Facebook, Instagram, and LinkedIn ads** to reach potential customers based on demographics & interests.  
- Create **educational content** (e.g., product tutorials, reviews, and comparisons) to attract tech-savvy buyers.  

✅ **Upsell & Cross-Sell Strategies**  
- Recommend **related accessories & premium upgrades** during checkout.  
- Use **email marketing** to promote **bundle deals & personalized offers** based on past purchases.  

---

## **4️⃣ Financial & Profitability Enhancements**  
✅ **Increase Profit Margins on High-Demand Items**  
- **Accessories & Headsets** have the highest orders—test **small price increases** to boost profitability.  
- Offer **subscription-based models** for frequently purchased products like storage devices or maintenance services.  

✅ **Reduce Operational Costs**  
- **Negotiate better supplier deals** for high-volume products.  
- Explore **automation & AI tools** to streamline order processing and reduce manual workload.  

✅ **Expand Payment & Financing Options**  
- Introduce **buy-now-pay-later (BNPL) options** to attract more customers.  
- Offer financing for **high-ticket items** like monitors & storage solutions.  

---

## **📌 Conclusion & Next Steps**  
Electromart has strong sales momentum, with **opportunities for expansion in products, regions, and customer engagement**. By implementing these **data-driven recommendations**, the business can **maximize revenue, improve customer retention, and enhance operational efficiency**.  

💡 **Next Steps:**  
✅ Execute targeted marketing campaigns for high-income & technician segments.  
✅ Expand logistics capabilities in Alberta & British Columbia.  
✅ Optimize pricing and inventory for maximum profitability.  
✅ Introduce loyalty programs & personalized recommendations to retain top customers.  

🚀 **With these strategies, Electromart can achieve sustained growth and long-term success!**  


## 📌 Conclusion 1 
Despite a slight decline in monthly revenue and profit, the business shows **strong long-term growth**. The recent spike in orders suggests increased demand, with Ontario leading in both sales and profitability. Strategic focus on high-performing product categories and regions can drive further success. 

## 📌 Conclusion  2
The **majority of orders** come from **high-income customers and technicians**, indicating a strong market in those segments. The **steady increase in customer orders** suggests a growing customer base. Mr. Joseph Bates is the **top customer by revenue**, contributing significantly to total sales.  

**Actionable insights:**  
- Focus marketing efforts on high-income customers and technicians.  
- Engage top customers with loyalty programs or exclusive offers.  
- Continue monitoring trends to sustain order growth.





## 📌 Conclusion  4
Ontario and Quebec are the **strongest sales regions**, with Toronto leading at the city level. Sales distribution suggests **strategic marketing efforts** should focus on high-performing cities while also expanding presence in growing regions like **Alberta and British Columbia**.  

**Actionable insights:**  
- Optimize inventory and logistics in Ontario and Quebec to meet demand.  
- Expand marketing in high-growth regions like Alberta and British Columbia.  
- Leverage city-level trends to tailor regional promotions.  


