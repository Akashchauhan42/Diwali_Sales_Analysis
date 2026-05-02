# 🎇 Diwali Sales Analysis

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on Diwali sales data using Python. The goal is to analyze customer purchasing behavior and identify key business insights to improve business decisions.

---

## 🎯 Objectives
- Analyze customer demographics (Gender, Age, Marital Status)
- Identify top-performing states and regions
- Find most popular product categories
- Understand spending patterns across occupations

---

## 🛠️ Tech Stack
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset Features
The dataset includes:
- User_ID  
- Gender  
- Age Group  
- State  
- Marital Status  
- Occupation  
- Product Category  
- Orders  
- Amount  

---

## 🧹 Data Cleaning
- Removed irrelevant columns (`Status`, `unnamed1`)
- Handled missing values using `dropna()`
- Converted `Amount` column to integer
- Checked and fixed inconsistencies

---

## 📊 Exploratory Data Analysis

### 👥 Customer Insights
- Majority buyers are **female customers**
- Age group **26–35** contributes the most

### 🌍 Regional Insights
Top contributing states:
- Uttar Pradesh  
- Maharashtra  
- Karnataka  

### 💼 Occupation Insights
Highest spending observed in:
- IT Sector  
- Healthcare  
- Aviation  

### 🛍️ Product Insights
Top product categories:
- Food  
- Clothing  
- Electronics  

---

## 📈 Key Findings
- Married women aged **26–35 years** are the primary buyers  
- Tier-1 states contribute maximum revenue  
- Certain occupations show higher purchasing power  

---

## 📉 Visualizations
- Bar Charts  
- Count Plots  
- Heatmaps  

(All visualizations created using Matplotlib & Seaborn)

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/Diwali-Sales-Analysis.git

# Navigate to project folder
cd Diwali-Sales-Analysis

# Install dependencies
pip install numpy pandas matplotlib seaborn

# Run Jupyter Notebook
jupyter notebook
