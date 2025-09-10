# 📊 The Look E-commerce - Customer & Marketing Analytics Dashboard (Power BI)

## 🔹 Problem Statement
E-commerce businesses rely on both effective marketing and deep customer understanding to grow profitably. Yet, identifying which channels deliver the best ROI, which customer segments are most valuable, and how to reduce churn is a challenge.  

The goal of this project was to analyze *The Look* E-commerce dataset using Power BI, focusing on **customer behavior and marketing performance**. The analysis aimed to uncover actionable insights into customer segmentation, campaign effectiveness, and acquisition channels to help optimize engagement and retention strategies.

---

## 🔹 Methodology
1. **Data Acquisition & Cleaning**  
   - Imported *The Look* E-commerce dataset from BigQuery into Power BI.  
   - Focused on customer-related and marketing-related tables: users, campaigns, and web events.  
   - Cleaned and transformed data in Power Query (handled missing values, corrected data types, removed duplicates).  

2. **Exploratory Data Analysis (EDA)**  
   - Segmented customers by demographics (gender, age, geography) and purchasing behavior.  
   - Built KPIs in DAX for customer lifetime value, acquisition costs, retention, and campaign ROI.  

3. **Dashboard Development**  
   - Created interactive dashboards with drill-downs by customer segment and marketing channel.  
   - Designed visualizations to compare campaign performance and understand customer engagement patterns.  

4. **Business Insights & Recommendations**  
   - Identified high-value customer segments and their preferred products.  
   - Highlighted most effective marketing channels by conversion and ROI.  
   - Recommended demographic-specific marketing strategies and retention initiatives.  

---

## 🔹 Key Business Questions
- Who are the most valuable customers and what are their purchasing behaviors?  
- Which marketing channels deliver the highest ROI and conversion rates?  
- How can campaigns be optimized to increase customer retention and reduce churn?  
- What actions can reduce cart abandonment and improve repeat purchases?  

---

## 🔹 Final Insights & Recommendations
1. **Customer Segmentation**:  
   - Female customers responded strongly to *Intimates*.  
   - Male customers showed higher interest in *Jeans* and *Underwear*.  

2. **Channel Optimization**:  
   - Email was the strongest converting channel, followed by Adwords.  
   - Suggested deeper cost analysis of Adwords before scaling.  

3. **Demographic Targeting**:  
   - Campaigns for customers aged 46–60 should be language- and lifestyle-specific.  

4. **Geographic Strategy**:  
   - Increase marketing investment in China, US, and Brazil (highest-performing markets).  

5. **Retention Focus**:  
   - Cart abandonment rate ~70% (industry benchmark) → implement 10+ day retargeting campaigns to recover lost sales.  

---

## 🔹 Dashboard Preview
(Add screenshots of your customer & marketing dashboards here)

![Customer Dashboard](./screenshots/customer_dashboard.png)  
![Marketing Performance](./screenshots/marketing_dashboard.png)  

---

## 🔹 Tools & Technologies
- **Power BI** (data modeling, visualization, DAX)  
- **Power Query** (data cleaning & transformation)  
- **BigQuery** (data source for The Look dataset)  

---

## 🔹 Dataset
- Source: [The Look E-commerce dataset](https://console.cloud.google.com/marketplace/product/bigquery-public-data/thelook-ecommerce) (Google BigQuery)  
- Type: Synthetic dataset simulating a real-world e-commerce retailer  

---

## 🔹 How to Explore
- Download the `.pbix` file from this repo and open it in Power BI Desktop.  
- Or explore the **live dashboard** here: [🔗 Power BI Report](INSERT-YOUR-LINK-HERE)  

---

👩‍💻 *This project was developed collaboratively during my Data Analytics Bootcamp at Le Wagon. My contribution focused on **customer analytics and marketing performance**, while teammates explored other business areas such as sales and logistics.*
