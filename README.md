# 📊 Credit Card Analytics Dashboard

## 📌 Project Overview
This project showcases an **interactive Credit Card Analytics Dashboard** built using **MySQL** and **Power BI**.  
It analyzes **customer behavior, transaction trends, revenue distribution, and credit card usage patterns** across multiple dimensions such as age group, income group, card category, geography, and time.

The project demonstrates an **end-to-end data analytics pipeline** from CSV ingestion into MySQL to visualization and insight generation in Power BI.

---

## 🗂️ Data Sources

### 1️⃣ Customer Data (`cust_detail`)
- Customer demographics  
- Age group, income group, marital status  
- Customer satisfaction score (CSS)  
- Job type, dependents, state  

### 2️⃣ Transaction Data (`cc_detail`)
- Weekly credit card transactions  
- Transaction amount and count  
- Card category (Blue, Silver, Gold, Platinum)  
- Usage type (Swipe, Chip, Online)  
- Interest earned and utilization ratio  

Data was loaded into MySQL using the `LOAD DATA INFILE` command from CSV files.

---

## 🛠️ Tech Stack
- **Database:** MySQL  
- **Data Ingestion:** CSV → MySQL (`LOAD DATA INFILE`)  
- **Visualization:** Power BI  
- **Modeling:** Relational data model  

---

## 📈 Dashboard Features

### 🔹 Credit Card Customer Report
- Total Revenue, Total Interest, Customer Satisfaction Score (CSS)  
- Weekly revenue trends  
- Revenue distribution by:
  - Age Group  
  - Income Group  
  - Marital Status  
  - Job Type  
  - Top States  

### 🔹 Credit Card Transaction Report
- Total Revenue, Transaction Count, Transaction Amount  
- Quarterly revenue and transaction trends  
- Revenue analysis by:
  - Card Category  
  - Expenditure Type  
  - Transaction Mode (Swipe / Chip / Online)  
  - Customer Job Type  

---

## 🔗 Data Model
- `cust_detail` → Customer master data  
- `cc_detail` → Transaction / weekly fact data  
- Relationship created on `Client_Num`  

This model enables combined customer-level and transaction-level analysis.

---

## 🎯 Key Insights
- Blue card customers generate the highest revenue  
- Customers aged 40–60 contribute the most to total revenue  
- High-income customers dominate transaction volume  
- Swipe-based transactions are the most common  
- Revenue follows clear quarterly and weekly patterns  

---

## 🚀 Learning Outcomes
- Hands-on experience with MySQL data ingestion and transformation  
- Understanding of relational data modeling for BI  
- Power BI dashboard design and storytelling  
- Handling real-world issues such as duplicate keys and incremental data loads  

---

## 📌 Future Improvements
- Implement incremental refresh in Power BI  
- Add customer segmentation and churn analysis  
- Introduce forecasting and KPI alerts  
- Optimize the model into a star schema  

---

## 📎 Repository Contents
- Power BI dashboard file (`.pbix`)  
- Customer and Transaction Reports (PDF)  
- CSV datasets  
- SQL scripts for data loading  

---

## 🙌 Author
**Kashish Reshamwala**  
Data Analytics & BI Enthusiast  

