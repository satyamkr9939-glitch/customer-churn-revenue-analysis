# 📊 Customer Churn & Revenue Impact Analysis (SQL + Power BI)

![Dashboard] 

🚀 Analyzed customer churn patterns and identified **high-risk segments impacting revenue**
💡 Built a data-driven solution to **reduce churn and improve retention strategy**

---

## 💣 Why This Matters

Customer acquisition costs are **5–6x higher than retention**, making churn one of the biggest hidden revenue risks ([arXiv][1])

👉 Even small improvements in retention can significantly increase profitability.

---

## 🎯 Business Objective

* Identify customers likely to churn
* Understand drivers of churn
* Quantify revenue impact
* Recommend retention strategies

---

## 📊 Key Insights

### 🔴 KPI Snapshot

* Total Customers: XXXX
* Churned Customers: XXXX
* Churn Rate: **~XX%**

---

### 📉 Revenue Impact

* High churn segments contribute significantly to revenue loss
* Long-tenure customers generate more value but churn less

👉 Shows importance of **targeted retention strategies**

---

### 👥 Customer Segmentation

![Segment](dashboard/screenshots/segment_analysis.png)

* High churn observed in:

  * Low tenure customers
  * High monthly charges segment

👉 Indicates **pricing sensitivity + onboarding issues**

---

### 📊 Behavioral Drivers

![Drivers](dashboard/screenshots/drivers.png)

Key churn drivers:

* Short tenure
* High monthly charges
* Low engagement

---

## 🧠 My Approach

1. Cleaned and prepared dataset
2. Performed exploratory data analysis (EDA)
3. Identified churn patterns across segments
4. Quantified revenue impact of churn
5. Built Power BI dashboard for insights

---

## ⚙️ Workflow

```id="1jlwmf"
Raw Data → Data Cleaning → EDA → Churn Analysis → Dashboard → Insights
```

---

## 🧾 Key SQL Concepts Used

* Aggregations (COUNT, SUM, AVG)
* Customer segmentation
* Filtering high-risk groups
* Revenue impact calculations

---

## 📊 DAX Metrics

```DAX id="p3h1kl"
Churn Rate = 
DIVIDE([Churned Customers], [Total Customers])
```

```DAX id="p9t2sd"
Revenue Loss = 
SUMX(Churned_Customers, [Monthly Charges])
```

---

## 🎯 Business Recommendations

* Improve onboarding for new customers
* Offer targeted discounts for high-risk segments
* Focus retention efforts on high-value customers
* Monitor churn trends regularly

---

## 🛠️ Tech Stack

* SQL
* Power BI (DAX, Dashboard)
* Excel / CSV

---

## 📂 Project Structure

```id="9slx2o"
customer-churn-revenue-analysis/
│
├── data/
├── sql/
├── dashboard/
│   ├── powerbi.pbix
│   └── screenshots/
├── docs/
├── README.md
```

---

## 🚀 What Makes This Project Strong

* Focuses on **business impact (revenue loss)**
* Goes beyond churn prediction → explains **why churn happens**
* Combines **analysis + visualization + insights**

---

## 💡 One-Line Summary

👉 Built a churn analysis solution to identify high-risk customers and reduce revenue loss through data-driven retention strategies.

---

## 🔗 Connect

* LinkedIn: https://www.linkedin.com/in/satyam-8b105032b
* GitHub: https://github.com/satyamkr9939-glitch

---

[1]: https://arxiv.org/abs/2304.10604?utm_source=chatgpt.com "Causal Analysis of Customer Churn Using Deep Learning"
