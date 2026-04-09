# 🚀 Customer Churn & Revenue Loss Analysis

> 🔍 Identified **33% churn rate** causing **₹99M+ revenue loss** using SQL-based analysis on 100K+ customer records

---

## 📌 Project Overview

This project analyzes customer churn behavior to uncover **revenue loss drivers, high-risk customer segments, and data-backed retention strategies**.

The analysis focuses on answering:
- Why are customers leaving?
- Which customers are most valuable?
- How much revenue is being lost due to churn?

---

## 🎯 Business Objective

- Identify churn patterns and key drivers  
- Quantify **revenue loss due to churn**  
- Detect high-value customer risk  
- Provide actionable retention strategies  

---

## 📊 Dataset

- Source: Synthetic Telco Customer Dataset (100,000 records)  
- Features include:
  - Customer demographics  
  - Tenure  
  - Monthly & total charges  
  - Contract type  
  - Payment method  
  - Churn status  

---

## 🧹 Data Cleaning

- Handled missing values in `TotalCharges`  
- Converted data types for accurate calculations  
- Checked for duplicates and inconsistencies  

---

## 📈 Key Metrics

- 👥 Total Customers: **100,000**  
- 📉 Churn Rate: **33.14%**  
- 💰 Total Revenue: **₹292.6M**  
- 💸 Revenue Lost: **₹99.7M (~34%)**

---

## 🔍 Key Insights

### 🚨 1. High Churn Problem
> 1 out of every 3 customers is leaving, indicating a major retention issue.

---

### 💸 2. High-Value Customers Drive Loss
- ₹85M+ loss from high-value segment  
- **~86% of total revenue loss**

> High-value customers are the primary contributors to revenue loss.

---

### 📉 3. Contract Type is the Main Driver
- Month-to-month churn: **~47%**  
- Long-term churn: **~16–18%**

> Month-to-month customers churn nearly **3x more** than long-term users.

---

### ⏳ 4. Early Churn Risk
- First-year churn: **67.41% 🚨**

> New customers are the most vulnerable segment.

---

### 💳 5. Customer Value Insight
- Churned customers have **higher average CLV**

> Losing high-value customers significantly impacts revenue.

---

## 📊 SQL Analysis Highlights

- Churn rate calculation  
- Revenue loss estimation  
- Customer segmentation (High / Medium / Low value)  
- Window functions (RANK) for prioritization  
- Cohort analysis (tenure-based churn)  
- CLV (Customer Lifetime Value) estimation  
- Pareto analysis (revenue contribution)  
- Anomaly detection (high-paying early churners)  

---

## 📂 Project Structure

