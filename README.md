# 📈 Profit Analysis Using Linear Regression & Power BI

## 📌 Project Overview

This project focuses on analyzing startup investment data and predicting profit using a **Linear Regression Machine Learning model**. The analysis explores how **R&D Spend, Administration Cost, and Marketing Spend** impact company profit. Interactive dashboards were built in **Power BI** to visualize trends, insights, and model performance.

---

## 🎯 Business Problem

Organizations invest heavily in R&D, marketing, and administration but often struggle to understand which factors contribute most to profitability.

This project aims to:

* Identify key profit-driving factors.
* Analyze spending patterns across states.
* Predict future profits using machine learning.
* Support data-driven investment decisions.

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Power BI

---

## 📂 Dataset Features

| Feature         | Description                         |
| --------------- | ----------------------------------- |
| R&D Spend       | Research and Development Investment |
| Administration  | Administrative Expenses             |
| Marketing Spend | Marketing Investment                |
| State           | Startup Location                    |
| Profit          | Target Variable                     |

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning

* Checked missing values
* Removed unnecessary columns
* Validated data types

### 2️⃣ Exploratory Data Analysis (EDA)

* Distribution analysis
* Correlation analysis
* Feature relationship analysis

### 3️⃣ Feature Engineering

* Encoded categorical variable (State)
* Prepared data for machine learning

### 4️⃣ Model Building

* Train-Test Split
* Linear Regression Model
* Profit Prediction

### 5️⃣ Model Evaluation

Performance Metrics:

| Metric           | Value |
| ---------------- | ----- |
| R² Score (Train) | 0.95  |
| R² Score (Test)  | 0.92  |
| MAE              | 6.31K |
| RMSE             | 7.80K |

---

## 📊 Dashboard Highlights

### Overview Dashboard

* Total Startups: **50**
* Total Profit: **5.60M**
* Average Profit: **112K**
* Total R&D Spend: **3.69M**
* Total Advertising Spend: **6.07M**
* Total Marketing Spend: **10.55M**

### Key Visualizations

* R&D Spend vs Profit
* Administration vs Profit
* Marketing Spend vs Profit
* Startups by State
* Average Profit by State

---

## 🤖 Regression Model

### Linear Regression Equation

```text
Profit = 48,091.40
        + (0.7856 × R&D Spend)
        - (0.0055 × Administration)
        + (0.0325 × Marketing Spend)
```

### Interpretation

* R&D Spend has the strongest positive impact on profit.
* Marketing Spend positively influences profit.
* Administration expenses have minimal impact on profit.

---

## 🔍 Key Insights

### 📈 R&D Drives Profit

Strong positive correlation observed between R&D investment and profit generation.

### 📢 Marketing Supports Growth

Higher marketing expenditure generally leads to increased profit.

### 🏢 State-Wise Performance

* Florida recorded the highest average profit.
* New York followed closely.
* California had the largest startup presence.

### 🎯 Model Accuracy

The model achieved:

* 95% training accuracy
* 92% testing accuracy

indicating strong predictive performance.

---

## 💡 Recommendations

* Increase investment in R&D activities.
* Optimize marketing budgets for maximum ROI.
* Monitor administrative costs.
* Use predictive analytics for future investment planning

## 🚀 Project Outcomes

✔ Built a predictive profit model using Linear Regression
✔ Achieved high model accuracy (R² = 0.92)
✔ Created interactive Power BI dashboards
✔ Identified key business drivers influencing profitability
✔ Generated actionable recommendations for decision-making

---

##Author

**Gopi santhosh reddy**
Aspiring Data Analyst | SQL | Power BI | Python | Machine Learning

