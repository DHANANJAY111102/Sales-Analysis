# Sales-Analysis

## Project Summary

This project centers on **exploratory data analysis (EDA)** and data visualization to uncover meaningful insights from sales data.
The objective is to examine customer characteristics, buying behavior, and regional performance so businesses can better understand their customers and make informed strategic decisions.

## Objectives
- Perform data cleaning and preprocessing to ensure reliable analysis  
- Identify sales trends on the basis of:
  - Gender  
  - Age groups  
  - Marital status  
  - States and zones  
  - Product categories  
  - Occupations  
- Calculate and visualize **Average Order Value (AOV)** across states and age groups.  
- Discover top-performing regions and product categories.

---

## Dataset Information
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

## Data Cleaning Steps
1. Removed null values in the `Amount` column.  
2. Converted `Marital_Status` to categorical labels:
   - `0` → `Married`
   - `1` → `Unmarried`
3. Ensured correct data types for all numeric and categorical columns.  
4. Dropped irrelevant or missing entries to maintain data quality.

---

## Exploratory Analysis & Visualizations
Key analysis performed using **Pandas**, **Matplotlib**, and **Seaborn**:

### 1. Gender Distribution
Visualized total customers by gender to understand overall audience composition.

### 2. Age Group vs. Sales
Compared **Age Groups** with **Total Revenue** and **Orders** segmented by Gender.

### 3. Marital Status vs. Spending
Explored how marital status influences total spending and order frequency.

### 4. Top Performing States
Identified the **Top 3 States** with the highest number of orders.

### 5. Occupation-based Revenue
Visualized which **Occupations** contribute most to the sales revenue.

### 6. Average Order Value (AOV)
Calculated AOV = `Revenue / Orders` for each state and age group.  
Top-performing states included:
- **Uttar Pradesh**
- **Maharashtra**
- **Karnataka**
- **Delhi**

### 7. Product Category Analysis
Pie chart showing the **Top 8 Product Categories** contributing to total sales.

---

## Key Insights
- **Females** have a slightly higher purchase rate compared to males.  
- **26–35** and **36–45** age groups generate the highest revenue.  
- **Married customers** tend to spend more on average.  
- **Uttar Pradesh, Maharashtra, and Karnataka** lead in both orders and revenue.  
- **Healthcare and Automobile** are the most profitable product categories.  
- The **average order value (AOV)** varies between ₹3,700–₹4,200 across regions.

---

## Tech Stack
- **Python** 🐍  
- **Libraries:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`  
- **Jupyter Notebook / VS Code**  
- **CSV File Handling & Data Visualization**

---

## 
