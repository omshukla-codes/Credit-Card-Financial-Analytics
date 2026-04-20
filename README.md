# 💳 Credit Card Financial Analytics Dashboard

## 📊 Overview
This project presents an **end-to-end Credit Card Analytics Dashboard** built using **SQL and Power BI**. It provides real-time insights into customer behavior, transaction trends, and key financial performance metrics.

## 🎯 Objective
To develop a comprehensive credit card weekly dashboard that provides real-time insights into key performance metrics and trends, enabling stakeholders to monitor and analyze credit card operations effectively.

## ⚙️ Project Workflow
1. Data extraction and storage using SQL  
2. Data cleaning and transformation  
3. Data modeling and relationship building  
4. DAX calculations for KPI generation  
5. Interactive dashboard creation in Power BI  
6. Insights generation for business decision-making  

## 🛠️ Tools & Technologies
- SQL (Data Storage & Querying)  
- Power BI (Data Visualization)  
- DAX (Data Analysis Expressions)  
- CSV (Data Source)  

## 📸 Dashboard Preview

### 🔹 Customer Insights Dashboard
![Customer Dashboard](powerbi/Credit%20Card%20Customer%20Insights%20Dashboard.png)

### 🔹 Transaction Analytics Dashboard
![Transaction Dashboard](powerbi/Credit%20Card%20Transaction%20Analytics%20Dashboard.png)

## 📐 Key DAX Calculations
- Revenue = Annual Fees + Total Transaction Amount + Interest Earned  
- Week Number calculation using `WEEKNUM()`  
- Current Week vs Previous Week Revenue  
- Customer segmentation using AgeGroup & IncomeGroup  

## 💡 Key Insights
- Total Revenue: **57M**  
- Total Interest Earned: **8M**  
- Total Transaction Amount: **46M**  
- Male customers contribute higher revenue (**31M**) than female (**26M**)  
- Blue & Silver cards contribute ~**93%** of transactions  
- Top contributing states: **TX, NY, CA (~68%)**  
- Activation Rate: **57.5%**  
- Delinquent Rate: **6.06%** 

## 🚀 How to Use
Download the `.pbix` file → Open in Power BI Desktop → Refresh data → Explore dashboard
