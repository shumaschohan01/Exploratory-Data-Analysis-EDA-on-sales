# 🧠 Exploratory Data Analysis (EDA) on Sales Data

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a **Superstore Sales Dataset**.  
The goal is to explore, understand, clean, and visualize the dataset to uncover **key business insights** and **data-driven patterns**.

EDA is the first and most crucial step in any data analysis or machine learning pipeline.  
It helps us understand data distribution, detect missing values or outliers, and identify relationships between variables.

---

## 🎯 Objectives

The main objectives of this project are:

- To understand the **structure, quality, and meaning** of the sales dataset.  
- To identify and handle **missing values** and **outliers**.  
- To perform **descriptive statistics** and **data visualization**.  
- To discover patterns, relationships, and insights from the data.  
- To prepare a clean dataset for potential **machine learning models** or **business reporting**.

---

## 🏢 Business Understanding

### 🔸 Problem Statement
A retail superstore wants to analyze its sales data to improve business performance.  
The dataset includes details like order date, customer, sales, profit, region, and product category.

### 🔸 Business Goals
- Identify top-performing products and categories.
- Discover which regions or segments generate the most profit.
- Find patterns in customer purchasing behavior.
- Detect any operational inefficiencies (e.g., shipping costs or delays).
- Provide recommendations to enhance profitability.

### 🔸 Target Variables
- **Sales** (Total revenue generated)
- **Profit** (Net income per transaction)

---

## 📊 Dataset Information

### 📂 Dataset Used
- File: `Superstore.xlsx`
- Type: Excel file (converted to CSV for analysis)

### 🧾 Columns Overview
The dataset contains multiple attributes such as:

- Order ID  
- Customer ID  
- Segment  
- Region  
- Category  
- Sub-Category  
- Sales  
- Quantity  
- Discount  
- Profit  
- Order Date  
- Ship Mode  

---

## 🧩 Step 1: Understanding the Problem and Data

Before starting any analysis, it’s important to understand:

- **What question are we trying to answer?**
- **What does each column mean?**
- **What type of data do we have?**

### ✅ Key Actions:
- Defined the **business problem** and **goal**.
- Identified **target variables** and **supporting features**.
- Determined possible **Key Performance Indicators (KPIs)** such as:
  - Total Sales
  - Total Profit
  - Average Discount
  - Profit Margin (%)
  - Customer Retention Rate

### 💡 Outcome:
A clear roadmap to perform structured and goal-oriented EDA.

---

## 🧭 Step 2: Importing and Inspecting the Data

The dataset was imported using **Pandas** in Python.

### ✅ Key Tasks:
- Loaded data without loss or corruption.
- Checked number of rows and columns.
- Displayed first few rows using `head()`.
- Verified data types of each column.
- Generated summary statistics with `describe()`.
- Checked for missing values.
- Identified unique values and categorical variables.

### 📋 Sample Code:
```python
import pandas as pd

df = pd.read_excel("Superstore.xlsx")
print(df.info())
print(df.describe())
print(df.head())
