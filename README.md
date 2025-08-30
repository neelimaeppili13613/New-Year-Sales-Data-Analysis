
# New Year Sales Data Analysis

This project analyzes **New Year Sales Data** to uncover customer behavior, trends, and insights.  
It follows a structured **Exploratory Data Analysis (EDA)** approach using Python, Pandas, Matplotlib, and Seaborn.

---

## 📌 Overview

Festive seasons such as New Year lead to a significant increase in sales for retailers.  
Understanding customer behavior during this period is crucial to maximize revenue, optimize inventory, and design targeted marketing campaigns.  

This project aims to answer key business questions like:  
- Which customer segments (gender, age, marital status) contribute the most to sales?  
- Which states and regions generate the highest number of orders and revenue?  
- Which occupations and product categories are the most profitable?  
- What customer profile represents the **high-purchasing group**?  

The findings can help businesses refine their **marketing strategies, customer targeting, and product stocking decisions** during high-demand festive periods.  

---

## 📂 Dataset Details

The dataset used in this project is **New Year Sales Data.csv**, which contains transactional records of customers.  

### Columns:
- **User_ID** → Unique identifier for each customer  
- **Cust_name** → Customer’s name  
- **Product_ID** → Unique product code  
- **Gender** → Customer’s gender (M/F)  
- **Age Group** → Age group (e.g., 0–17, 18–25, 26–35, etc.)  
- **Age** → Exact age of customer  
- **Marital_Status** → Customer’s marital status (0 = Single, 1 = Married)  
- **State** → State of residence  
- **Zone** → Geographical zone of the state  
- **Occupation** → Customer’s profession/industry  
- **Product_Category** → Category of purchased product (e.g., Auto, Clothing, Food, Electronics, etc.)  
- **Orders** → Number of items purchased in the transaction  
- **Amount** → Total amount spent in the transaction  
- **Status / unnamed1** → Extra columns (removed during cleaning)  

### Size:
- Rows: Multiple thousands of transaction records  
- Columns: 13 (after cleaning, 11 useful columns remain)  

---

## 📊 Steps Performed

### 1. Import Libraries
- pandas, numpy, matplotlib, seaborn

### 2. Load and Explore Dataset
- Load CSV file
- Preview first few rows

### 3. Data Cleaning
- Handle missing values
- Drop unnecessary columns (`Status`, `unnamed1`)
- Convert `Amount` column to integer

### 4. Data Overview & Summary
- Generate descriptive statistics
- Explore unique values in each column

### 5. Exploratory Data Analysis (EDA)
Performed visual analysis using **matplotlib** (mostly) and **seaborn** (only for grouped plots).

- **Gender Analysis**
  - Count of customers by gender
  - Total purchase amount by gender

- **Age Group Analysis**
  - Purchases by age group and gender
  - Total amount spent by each age group

- **State Analysis**
  - Top 10 states by orders
  - Top 10 states by revenue

- **Marital Status Analysis**
  - Count by marital status
  - Total purchase amount by marital status and gender

- **Occupation Analysis**
  - Sales distribution across occupations
  - Total revenue by occupation

- **Product Category Analysis**
  - Popular product categories
  - Revenue contribution of each product category

---

## ✅ Insights

- **Female customers** spent more than male customers.  
- **Age group 26–35** contributed the highest sales.  
- **Top states** include Maharashtra, Karnataka, and Uttar Pradesh.  
- **Married women** were major buyers.  
- **Top contributing occupations**: IT, Healthcare, and Aviation.  
- **Food, Clothing, and Electronics** were the most purchased categories.

---

## 🚀 How to Run

1. Clone/download this project.  
2. Open Jupyter Notebook.  
3. Run the cells in `notebook.ipynb` sequentially.  
4. Ensure `New Year Sales Data.csv` is in the same folder as the notebook.  

---

## 🔮 Possible Extensions

- Analyze purchase trends by **season/month**.  
- Study correlation between **age and spending amount**.  
- Analyze preferences for **product categories by gender**.  
- Predict customer segments using ML models.  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- Numpy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📌 Author

Project created as part of a **New Year Sales Analysis** assignment.  

