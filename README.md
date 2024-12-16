# 🚀 **Warehouse-And-Retail-Sales and Data Exploration** 📊  

![Warehouse Sales GIF](https://images.squarespace-cdn.com/content/v1/5f998d41303db018cd809687/16bdb895-eaad-4beb-a60f-fe0fb1d02c0d/Row-of-colorful-wine-bottles-sitting-in-front-of-a-textured-green-gray-wall.jpg)   

---

## 📝 **Project Overview**  

This project focuses on clustering products using **historical sales data** to optimize **inventory management**, identify **market trends**, and tailor **product offerings**.

---

## 🎯 **Goals and Objectives**  

### 🚦 **Goals**:  
1. **Optimize Inventory**: Prevent overstocking/understocking.  
2. **Empower Insights**: Drive decisions in marketing and sales.  
3. **Competitive Edge**: Stay ahead using data-driven analysis.  

### 🎯 **Objectives**:  
- 📌 Conduct clustering analysis to group similar products.  
- 📊 Create insightful visualizations and dashboards.  
- 🛠 Document methodology for reproducibility.  

---

## 🛠 **Key Features**  

| 🏷️ **Feature**             | 🧩 **Details**                                                                 |
|-----------------------------|------------------------------------------------------------------------------|
| 📅 **Time Frame**           | Analyzes data from **2017–2020**.                                             |
| 🔍 **Clustering Approach**  | Uses sales **patterns and attributes** to group products.                    |
| 📈 **Exploratory Analysis** | Trends on **Sales**, **Transfers**, and **Returns** across **years**.        |
| 🧹 **Data Cleaning**        | - Handled **null values** and **outliers** <br> - Transformed and renamed columns |

---

## 📊 **Dataset Insights**  

- **Size**: 307,645 rows × 9 columns.  
- **Volume**: 21.1 MB.  
- **Key Metrics**:  
    - **Warehouse Sales** 📦: Major stock activity.  
    - **Retail Sales** 🛒: Customer purchase trends.  
    - **Returns** 🔄: Focus area to improve efficiency.  

---

## 🔍 **Data Cleaning Summary**  

### ✨ **Missing Values**  
- 🗂️ `SUPPLIER` → Replaced with **"YEAR"**  
- 🏷️ `ITEM TYPE` → Filled with **"NON-ALCOHOL"**  
- 💰 `RETAIL SALES`, `RETAIL TRANSFERS` → Replaced with **0**  

### ✨ **Transformation**  
- Columns like `ITEM CODE` converted for **numerical clustering**.  
- 🏷️ New fields: **BRAND NAME**, **UNITS**, and **STD UNIT**.  

### ✨ **Outliers**  
- Outliers identified in **Warehouse Sales** and **Retail Transfers**.  

---

## 📈 **Exploratory Data Analysis (EDA)**  

![Data Trends GIF](https://media1.tenor.com/m/CNhGbA8yH9IAAAAd/beer-wine.gif)  

---

### 📊 **Major Insights**  

1. 🛒 **Retail Sales by Year**:  
   ![Retail Sales Graph](graphs/retail_sales_2017_2020.png)  
   - **Best Year**: 2019 (44.4%)  
   - **Lowest**: 2020 (Post-COVID impact).  

---

2. 📦 **Warehouse Sales by Year**:  
   ![Warehouse Sales Graph](graphs/warehouse_sales_2017_2020.png)  
   - **Peak Activity** in 2019: **45.9%**.  

---

3. 🔄 **Returns Trends**:  
   ![Returns Graph](graphs/returns_trends.png)  
   - High **Return Rate** in **2017**: **71.4%**.  

---

4. 🚚 **Transfers Trends (Monthly)**:  
   ![Transfers Graph](graphs/transfers_monthly.png)  
   - Highest transfers seen in **June and December**.  

---

5. 📊 **Yearly Comparison**:  
   ![Year Comparison Graph](graphs/year_comparison.png)  
   A holistic view of **Retail Sales**, **Warehouse Sales**, and **Transfers** across years.

---

## 🖼️ **More Charts**  

| 📊 **Chart Title**                     | 📈 **Graph File**                    |  
|---------------------------------------|-------------------------------------|  
| 🏷️ **Monthly Sales Trends (2017)**    | `graphs/sales_trends_2017.png`      |  
| 🏷️ **Warehouse Sales vs Transfers**   | `graphs/warehouse_vs_transfers.png` |  
| 🏷️ **Returns by Product Category**    | `graphs/returns_by_category.png`    |  
| 🏷️ **Retail vs Warehouse Comparison** | `graphs/retail_vs_warehouse.png`    |  

---

## 🤖 **Next Steps: Machine Learning** 🧠  

With all insights gathered, we are now ready to implement **machine learning models** to predict product clusters and optimize inventory.  

---

## 📌 **Target Audience** 👥  
- 📊 **Business Managers**: Inventory & strategy decisions.  
- 🎯 **Marketing Teams**: Design campaigns.  
- 💻 **Data Analysts**: Insights and data tools.  
- 🏢 **Market Stakeholders**: Competitive growth strategies.  

---

## 🎉 **Conclusion** 🌟  

This project delivers actionable insights into sales trends, stock optimization, and clustering analysis. Ready to take this further? Let’s **dive into predictions** and transform operations with machine learning! 🚀  

---

📄 **Report Author**: *Nikhil Umredkar*  
🔗 **Project Repository**: *[Link to Repo]*  

---
