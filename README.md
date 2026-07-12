# 📈 Retail Sales Forecasting & Demand Intelligence System

> An end-to-end Machine Learning project that analyzes historical retail sales data, detects demand patterns, forecasts future sales, identifies anomalies, and provides actionable business insights for inventory and supply chain management.

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-red)
![XGBoost](https://img.shields.io/badge/XGBoost-Forecasting-green)
![SARIMA](https://img.shields.io/badge/SARIMA-Time%20Series-purple)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

# 📌 Project Overview

Retail companies often struggle with balancing inventory levels. Overstocking increases storage costs, while understocking results in lost sales and dissatisfied customers.

This project uses **Exploratory Data Analysis (EDA)**, **Machine Learning**, and **Time Series Forecasting** to help businesses predict future sales, identify unusual demand patterns, and optimize inventory decisions.

The system provides valuable insights that can be used by:

- Head of Supply Chain
- Chief Financial Officer (CFO)
- Inventory Managers
- Business Analysts
- Operations Teams

---

# 🎯 Objectives

- Analyze historical retail sales data.
- Understand customer purchasing behavior.
- Detect seasonal demand patterns.
- Identify sales anomalies.
- Forecast the next three months of sales.
- Segment products based on demand.
- Recommend inventory strategies.
- Support business decision-making using data.

---

# 📊 Features

✅ Data Cleaning & Preprocessing

✅ Exploratory Data Analysis (EDA)

✅ Monthly & Yearly Sales Trend Analysis

✅ Category-wise Sales Analysis

✅ Regional Performance Analysis

✅ Seasonal Pattern Detection

✅ Time Series Forecasting

✅ SARIMA Forecasting Model

✅ Prophet Model Comparison

✅ XGBoost Forecasting

✅ Forecast Accuracy Evaluation

- MAE
- RMSE
- MAPE

✅ Confidence Interval Prediction

✅ Sales Anomaly Detection

✅ Product Demand Segmentation

✅ Inventory Optimization Recommendations

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-Learn | Machine Learning |
| Statsmodels | SARIMA Forecasting |
| Prophet | Time Series Forecasting |
| XGBoost | Machine Learning Forecasting |
| Jupyter Notebook | Development Environment |

---

# 📂 Project Structure

```
Retail-Sales-Forecasting/
│
├── analysis.ipynb
├── train.csv
├── test.csv
├── summary.docx
├── summary.pdf
├── images/
│   ├── sales_trend.png
│   ├── forecast.png
│   ├── anomaly.png
│   └── segmentation.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

# 📈 Workflow

```
Historical Sales Data
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Forecasting Models
        │
        ▼
Model Evaluation
        │
        ▼
Demand Forecast
        │
        ▼
Business Insights
        │
        ▼
Inventory Recommendations
```

---

# 📊 Exploratory Data Analysis

The project performs detailed business analysis including:

- Monthly Sales Trend
- Yearly Revenue Trend
- Sales by Product Category
- Sales by Region
- Customer Purchase Behavior
- Seasonal Sales Analysis
- Correlation Analysis
- Distribution Analysis

Key findings include:

- Technology products generate the highest revenue.
- Sales peak during the holiday season.
- Seasonal demand is consistent across years.
- Regional demand remains relatively stable.

---

# 🤖 Forecasting Models

Three forecasting approaches were compared.

| Model | Purpose |
|--------|----------|
| SARIMA | Time Series Forecasting |
| Prophet | Seasonal Forecasting |
| XGBoost | Machine Learning Forecasting |

Performance Metrics:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)

The model with the lowest forecasting error was selected as the final forecasting model.

---

# 📉 Forecast Output

The system predicts future sales for the next **3 months** along with confidence intervals.

Example Output

| Month | Forecast | Confidence Range |
|--------|-----------|-----------------|
| January | 43,492 | 39,000–48,000 |
| February | 34,805 | 30,000–40,000 |
| March | 69,907 | 62,000–76,000 |

---

# 🚨 Anomaly Detection

The project automatically identifies unusual sales behavior.

Examples include:

- Holiday sales spikes
- Unexpected sales drops
- Regional demand surges
- Promotional campaign effects

Understanding these anomalies helps improve inventory planning and demand forecasting.

---

# 📦 Product Demand Segmentation

Products are categorized into:

### 🔥 High Demand

- Maintain higher inventory
- Weekly replenishment
- Higher safety stock

### 📦 Medium Demand

- Moderate inventory
- Bi-weekly review

### 📉 Low Demand

- Lean inventory
- Monthly replenishment

---

# 💼 Business Recommendations

Based on the analysis, the system recommends:

### 1. Increase Inventory Before Peak Seasons

Historical data shows significant sales growth during holiday periods.

---

### 2. Prioritize High-Demand Products

Technology products consistently generate the highest revenue.

---

### 3. Use Forecasting for Procurement Planning

Forecast-driven purchasing reduces:

- Stock-outs
- Overstocking
- Warehouse costs

---

# ⚠️ Limitations

- Forecast accuracy depends on historical data.
- Unexpected market events may affect predictions.
- Economic changes and promotions can alter demand.
- Models require periodic retraining.

---

# 📷 Sample Visualizations

- Monthly Sales Trend
- Seasonal Trend
- Forecast Plot
- Confidence Interval
- Product Segmentation
- Correlation Heatmap
- Sales Distribution
- Anomaly Detection

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Retail-Sales-Forecasting.git
```

Move into the project

```bash
cd Retail-Sales-Forecasting
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

Open

```
analysis.ipynb
```

---

# 📋 Requirements

```
Python >= 3.10

pandas
numpy
matplotlib
seaborn
scikit-learn
statsmodels
prophet
xgboost
jupyter
```

---

# 📚 Future Improvements

- Deep Learning (LSTM)
- Real-time Sales Dashboard
- Power BI Integration
- Streamlit Web Application
- Automated Model Retraining
- Demand Forecast API
- Inventory Optimization Engine

---

# 👨‍💻 Author

**Harshvardhan Sinha**

---
