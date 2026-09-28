# 📊 Sri Lanka Monthly Inflation Dashboard

An interactive **Power BI dashboard** developed to analyze Sri Lanka's monthly inflation trends, explore relationships with key macroeconomic indicators, identify potential inflation drivers, and visualize forecasting model performance.

The dashboard covers monthly data from **2008 to 2024** and was developed as a **self-learning and practical data analytics project** to strengthen skills in Power BI, statistical analysis, forecasting, and data visualization.

---

## 📌 Project Overview

Inflation is one of the most important economic indicators for understanding changes in the general price level and overall economic conditions.

Sri Lanka experienced significant fluctuations in inflation during the period covered by this project, particularly around the economic crisis period.

This Power BI dashboard was developed to provide an interactive and easy-to-understand view of:

- Historical inflation movements
- Yearly and monthly inflation patterns
- Key economic indicators
- Relationships between inflation and macroeconomic variables
- Inflation forecasting results
- Forecasting model performance
- Potential drivers associated with changes in inflation

The dashboard combines **descriptive analysis, relationship analysis, forecasting, and interactive visualization** in a single report.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze monthly inflation trends in Sri Lanka
- Identify periods of high and low inflation
- Summarize important inflation statistics
- Visualize major macroeconomic indicators
- Explore relationships between inflation and selected economic variables
- Compare different inflation forecasting approaches
- Evaluate forecasting accuracy using error metrics
- Explore variables associated with increases in inflation
- Present statistical and economic information through an interactive Power BI dashboard

---

## 📅 Data Period

**2008 – 2024**

The dashboard contains **204 monthly observations**.

---

## 📊 Inflation Summary

Based on the dataset used in the dashboard:

| Measure | Value |
|---|---:|
| Number of Months | 204 |
| Minimum Inflation Rate | -2.10 |
| Maximum Inflation Rate | 69.80 |
| Average Inflation Rate | 9.13 |
| Median Inflation Rate | 5.20 |
| Variance of Inflation Rate | 169.63 |

These statistics provide a quick overview of the behavior and variability of inflation during the study period.

---

# 🖥️ Dashboard Pages

The Power BI report contains five main dashboard pages.

---

## 1️⃣ Inflation Overview

The **Inflation Overview** page provides a high-level summary of monthly inflation in Sri Lanka.

### Main Features

- Number of monthly observations
- Lowest inflation rate
- Highest inflation rate
- Average inflation rate
- Median inflation rate
- Variance of inflation
- Average inflation rate by year
- Monthly inflation trend
- Detailed monthly inflation table
- Year filter
- Month filter

This page allows users to quickly understand the overall behavior of inflation and identify major inflationary periods.

![Inflation Overview](screenshots/Inflation%20Overview.png)

---

## 2️⃣ Economic Indicators

The **Economic Indicators** page visualizes several macroeconomic variables that may be associated with inflation.

### Indicators Included

- Treasury Bill Rate
- Average Weighted Deposit Rate (**AWDR**)
- Average Weighted Prime Lending Rate (**AWPR**)
- Exchange Rate
- Imported Food and Drinks Unit Value Index
- Imported Petroleum Price
- Foreign Debt
- International Reserves

The page provides historical trend visualizations that make it easier to compare changes in major economic indicators over time.

Interactive **Year** and **Month** filters are also available.

![Economic Indicators](screenshots/Economic%20Indicators.png)

---

## 3️⃣ Relationship Analysis

The **Relationship Analysis** page explores associations between inflation and selected macroeconomic variables.

### Relationships Examined

- Exchange Rate vs Inflation
- AWPR vs Inflation
- Treasury Bill Rate vs Inflation
- Imported Petroleum Prices vs Inflation

Scatter plots and trend lines are used to visually examine whether inflation tends to move together with changes in these economic variables.

![Relationship Analysis](screenshots/Relationship%20Analysis.png)

> **Note:** These visual relationships represent statistical associations within the dataset. They should not automatically be interpreted as evidence of causality.

---

## 4️⃣ Forecast and Model Comparison

The **Forecast and Model Comparison** page presents inflation forecasting results and compares the performance of different forecasting methods.

### Forecasting Models

Two forecasting approaches are presented:

- **GAM + ARMA**
- **XGBoost**

### Dashboard Components

- 12-month inflation forecast
- Actual inflation values
- GAM + ARMA forecast
- XGBoost forecast
- Actual vs forecast comparison
- MAE comparison
- RMSE comparison

![Forecast and Model Comparison](screenshots/Forecast%20and%20Model%20Comparison.png)

---

# 🤖 Forecasting Models

## GAM + ARMA

A **Generalized Additive Model (GAM)** was used to capture nonlinear relationships in the data.

An **ARMA model** was then applied to the residual component to model remaining time-series behavior.

The final approach presented in the dashboard uses:

**GAM + ARMA(2,4)**

This approach combines nonlinear modeling with time-series residual correction.

---

## XGBoost

**XGBoost (Extreme Gradient Boosting)** was used as a machine-learning forecasting approach.

The model was trained using historical inflation information and relevant features to capture complex nonlinear patterns in the data.

The model provides an alternative to traditional statistical forecasting methods.

---

## 📏 Model Evaluation

Forecasting models were evaluated using:

### Mean Absolute Error — MAE

MAE measures the average absolute difference between actual and predicted values.

Lower MAE values indicate smaller average forecasting errors.

### Root Mean Squared Error — RMSE

RMSE gives greater weight to larger forecasting errors.

Lower RMSE values indicate better forecasting accuracy.

### Model Comparison

| Model | MAE | RMSE |
|---|---:|---:|
| GAM + ARMA(2,4) | 13.05 | 14.78 |
| XGBoost | 12.51 | 13.47 |

The dashboard allows these performance differences to be compared visually.

---

## 5️⃣ Inflation Drivers

The **Inflation Drivers** page uses Power BI's **Key Influencers** visual to explore variables associated with increases in inflation.

### Variables Examined

- Foreign Debt
- Treasury Bill Rate
- AWPR
- Exchange Rate

The Key Influencers visual identifies patterns in the available data and highlights variables associated with higher inflation values.

![Inflation Drivers](screenshots/Inflation%20Drivers.png)

> The Key Influencers results are exploratory and should be interpreted as associations rather than direct causal effects.

---

# 🛠️ Tools & Technologies

The following tools and techniques were used in this project:

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Data Cleaning**
- **Data Transformation**
- **Exploratory Data Analysis**
- **Statistical Analysis**
- **Time Series Analysis**
- **Forecasting**
- **Machine Learning**
- **Data Visualization**

---

# 📈 Analytical Techniques

The project incorporates several analytical components:

### Descriptive Analysis

Used to summarize inflation using:

- Mean
- Median
- Minimum
- Maximum
- Variance
- Historical trends

### Trend Analysis

Time-series visualizations were used to examine changes in inflation and economic indicators across the study period.

### Relationship Analysis

Scatter plots and trend lines were used to explore relationships between inflation and selected macroeconomic indicators.

### Forecasting

Statistical and machine-learning forecasting approaches were used to generate inflation predictions.

### Model Evaluation

Forecasting models were compared using MAE and RMSE.

### Driver Analysis

Power BI's Key Influencers visual was used to explore variables associated with increases in inflation.

---

# 💡 Skills Practiced

This project helped strengthen practical skills in:

- Power BI dashboard development
- Data preparation
- Data cleaning
- Power Query
- DAX
- Creating calculated measures
- Dashboard layout and design
- Interactive filtering
- KPI development
- Time-series visualization
- Economic data analysis
- Statistical interpretation
- Forecast visualization
- Machine-learning model comparison
- Communicating analytical results visually

---

# 📂 Repository Structure

```text
Sri-Lanka-Monthly-Inflation-Dashboard/
│
├── Sri Lanka Monthly Inflation Dashboard.pbix
│
├── README.md
│
└── screenshots/
    ├── Inflation Overview.png
    ├── Economic Indicators.png
    ├── Relationship Analysis.png
    ├── Forecast and Model Comparison.png
    └── Inflation Drivers.png
```

---

# 🚀 How to Use the Dashboard

### Step 1

Download the following file from this repository:

```text
Sri Lanka Monthly Inflation Dashboard.pbix
```

### Step 2

Install **Microsoft Power BI Desktop** if it is not already installed.

### Step 3

Open the `.pbix` file using Power BI Desktop.

### Step 4

Navigate through the dashboard pages:

```text
Inflation Overview
        ↓
Economic Indicators
        ↓
Relationship Analysis
        ↓
Forecast and Model Comparison
        ↓
Inflation Drivers
```

### Step 5

Use the interactive filters, charts, tables, and visuals to explore the data.

---

# 📖 Dashboard Navigation

| Page | Purpose |
|---|---|
| Inflation Overview | Understand overall inflation patterns |
| Economic Indicators | Examine major economic variables |
| Relationship Analysis | Explore associations with inflation |
| Forecast and Model Comparison | Compare forecasting results |
| Inflation Drivers | Explore factors associated with inflation changes |

---

# ⚠️ Important Note

This project was developed primarily as a **self-learning and practice project**.

The dashboard is intended for:

- Data analysis practice
- Power BI practice
- Statistical visualization
- Forecasting practice
- Portfolio demonstration
- Educational purposes

The results should not be treated as official economic forecasts or financial advice.

Relationships shown in the dashboard indicate patterns observed in the available data and do not necessarily imply causal relationships.

---

# 🎓 Project Background

This project combines my academic knowledge in:

- Applied Statistics
- Financial Mathematics
- Time Series Analysis
- Forecasting
- Machine Learning

with practical skills in:

- Power BI
- Data Analytics
- Business Intelligence
- Data Visualization

The project was developed to demonstrate how statistical and economic data can be transformed into an interactive analytical dashboard.

---

# 🔮 Future Improvements

Possible future developments include:

- Adding more recent inflation data
- Connecting the dashboard to automatically updated data sources
- Adding additional macroeconomic indicators
- Improving forecasting model performance
- Including prediction intervals
- Adding more advanced DAX measures
- Expanding model evaluation metrics
- Developing an online version of the dashboard
- Adding additional machine-learning forecasting models

---

# 👤 Author

## Chamod Himesha

**BSc in Applied Statistics and Financial Mathematics**

### Areas of Interest

`Data Analysis` • `Statistics` • `Forecasting` • `Machine Learning` • `Business Intelligence` • `Power BI`

---

## ⭐ Support

If you find this project useful or interesting, feel free to give the repository a **⭐ Star**.

Feedback and suggestions are welcome.
