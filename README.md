# 📈 Sales-Analysis

## 📄 Project Summary

This project centers on **exploratory data analysis (EDA)** and data visualization to uncover meaningful insights from sales data.

The goal is to analyze customer demographics, purchasing behavior, and regional performance to support data-driven business decisions.

Through systematic data cleaning, aggregation, and visualization, the project highlights key revenue drivers and customer segments that contribute most to overall sales performance.


## 🎯 Objectives
- Clean and preprocess raw sales data to ensure analytical accuracy.
- Analyze sales performance across:
  - Age Groups
  - Gender    
  - Marital status  
  - States  
  - Product categories  
  - Occupations of buyers  
- Discover top-performing regions and product categories.

---

## 📁 Dataset Information
**Source:** `sales_data.csv`  
**Shape:** `11,251 rows × 13 columns`

| Column Name | Description |
|--------------|-------------|
| `User_ID` | Unique customer ID |
| `Cust_name` | Customer name |
| `Product_ID` | Product identifier |
| `Gender` | Gender of customer |
| `AGE_GROUP` | Categorical age group |
| `Age` | Actual age of customer |
| `Marital_Status` | 0 = Married, 1 = Unmarried |
| `State` | Customer's state |
| `Zone` | Regional zone |
| `Occupation` | Profession type |
| `Product_Category` | Type of product purchased |
| `Orders` | Number of orders placed |
| `Amount` | Total purchase amount |

---

## 🧹 Data Cleaning Steps
1. Removed null values in the `Amount` column.  
2. Converted `Marital_Status` into meaningful categorical labels:
   - `0` → `Married`
   - `1` → `Unmarried`
3. Eliminated irrelevant or incomplete entries to maintain analytical integrity.
4. Ensured correct data types for all numeric and categorical columns.  
   
---

## 📊 Exploratory Analysis & Visualizations
Analysis and visualizations were performed using **Pandas**, **Matplotlib**, and **Seaborn**.

### 1. Age Group vs. Sales Performance
Evaluated revenue and order volume across age groups, segmented by gender.

### 2. Customer Gender Distribution
Analyzed overall customer distribution by gender to understand audience composition.

### 3. Marital Status vs. Spending
Assessed the impact of marital status on total revenue and purchasing frequency.

### 4. Top-Performing States
Identified the **top three states** based on total order volume.

### 5. Revenue by Occupation
Analyzed which **occupational groups** contribute the highest revenue.

### 6. Average Order Value (AOV) Analysis
AOV = Total Revenue ÷ Total orders.
Top-performing states included:
- **Uttar Pradesh**
- **Maharashtra**
- **Karnataka**

### 7. Product Category Contribution
Visualized the **top four** product categories contributing to total sales using a pie chart.

---

## 🔍 Key Insights
- The **26–35** age groups generate the highest revenue
- **Female customers** demonstrate slightly higher purchasing activity than males   
- **Married customers** exhibit higher average spending behavior  
- **Uttar Pradesh**, **Maharashtra**, and **Karnataka** lead in both revenue and order volume
- **IT Sector** and **Healthcare** categories are the most profitable

---

## 🛠️ Tech Stack
- **Programming Language**: Python 
- **Libraries:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`  
- **Tools**: **Jupyter Notebook**  

---

## 
