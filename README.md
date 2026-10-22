# 🏥 Medical Database Analysis Using Excel

## 📌 Project Overview

This project focuses on analyzing medical and health-related data using Microsoft Excel. The dataset includes patient age, BMI, blood pressure, glucose, insulin, cholesterol, physical activity, and progression score.

The objective is to explore health indicators, identify patterns, analyze relationships between medical variables, and create meaningful insights using Excel data analysis and visualization tools.

## 🎯 Project Objectives

- Analyze patient demographic and health information.
- Identify BMI and blood pressure patterns.
- Examine glucose, insulin, and cholesterol levels.
- Explore the relationship between physical activity and health indicators.
- Analyze the distribution of progression scores.
- Build interactive dashboards using Excel charts, PivotTables, and slicers.
- Present data-driven insights in a simple and understandable format.

## 📊 Dataset Description

The dataset contains the following variables:

| Column | Description |
|---|---|
| Age | Patient age in years |
| BMI | Body Mass Index |
| Blood_Pressure | Blood pressure measurement |
| Glucose | Glucose measurement |
| Insulin | Insulin measurement |
| Cholesterol | Cholesterol measurement |
| Physical_Activity | Physical activity value recorded in the dataset |
| Progression_Score | Numerical progression score |

**Dataset size:** 3 sample records provided.

> Note: The units, measurement methods, and clinical reference ranges for the medical variables have not been specified. They should be verified before interpreting results.

## 🗂️ Sample Dataset

| Age | BMI | Blood Pressure | Glucose | Insulin | Cholesterol | Physical Activity | Progression Score |
|---:|---:|---:|---:|---:|---:|---:|---:|
| 58 | 40.67 | 134 | 77 | 174 | 200 | 10 | 73.82 |
| 71 | 38.39 | 66 | 160 | 83 | 276 | 0 | 80.22 |
| 48 | 23.94 | 133 | 156 | 46 | 203 | 10 | 63.90 |

## 🛠️ Tools and Technologies

- **Microsoft Excel**
- Excel Tables
- Data Cleaning and Formatting
- Sorting and Filtering
- PivotTables and PivotCharts
- Conditional Formatting
- Excel Formulas
- Correlation Analysis
- Interactive Dashboard Creation

## 🔍 Data Analysis Process

### 1. Data Cleaning
- Check for missing values and duplicate records.
- Verify data types and numerical formats.
- Confirm units and measurement definitions.
- Identify inconsistent or invalid entries.

### 2. Exploratory Data Analysis (EDA)
- Calculate average, minimum, and maximum values.
- Analyze patient age and BMI distributions.
- Examine blood pressure, glucose, insulin, and cholesterol values.
- Summarize physical activity and progression scores.

### 3. Statistical Analysis

Use Excel functions such as:

- `AVERAGE()` – Calculate the mean.
- `MEDIAN()` – Find the median.
- `MIN()` and `MAX()` – Identify minimum and maximum values.
- `STDEV.S()` – Measure sample variability.
- `CORREL()` – Examine linear relationships between numerical variables.
- `COUNT()` and `COUNTBLANK()` – Check record counts and missing values.

Example formula to calculate the correlation between BMI and progression score:

`=CORREL(B2:B4,H2:H4)`

*Adjust the cell ranges to match the actual dataset.*

### 4. Data Visualization

Recommended Excel charts:

- **Column Chart:** Average cholesterol by age group.
- **Scatter Plot:** BMI versus progression score.
- **Bar Chart:** Physical activity by patient.
- **Histogram:** Distribution of glucose measurements.
- **Scatter Plot:** Blood pressure versus cholesterol.
- **KPI Cards:** Average age, BMI, cholesterol, and progression score.

## 📈 Dashboard KPIs

The Excel dashboard can include:

- Total patient records
- Average patient age
- Average BMI
- Average blood pressure
- Average glucose
- Average insulin
- Average cholesterol
- Average physical activity
- Average progression score

Use PivotTables, slicers, and charts to make the dashboard interactive.

## 💡 Preliminary Observations

Based on the three sample records:

- The highest BMI is approximately 40.67.
- The highest recorded cholesterol value is 276.
- The highest recorded glucose value is 160.
- The highest progression score is approximately 80.22.
- One record has a physical activity value of 0.

These observations describe only the supplied sample. They do not establish a medical diagnosis or a reliable population-level relationship.

## 📁 Project Structure

```text
medical-database-analysis/
│
├── README.md
├── medical_dataset.xlsx
├── analysis/
│ └── statistical_summary.xlsx
│
└── dashboard/
└── medical_dashboard.xlsx
```

*The filenames above are suggested project files; add them to your repository as you create them.*

## 🚀 How to Use

1. Download or clone this GitHub repository.
2. Open `medical_dataset.xlsx` in Microsoft Excel.
3. Review and clean the dataset.
4. Perform descriptive and correlation analysis.
5. Create PivotTables and charts.
6. Build an interactive dashboard.
7. Document findings and limitations in the project.

## ⚠️ Disclaimer

This project is intended for educational and data-analysis purposes only. The dataset is small and does not establish clinical relationships or support medical diagnoses. Medical interpretations require verified units, appropriate clinical context, and qualified professional review.

## 👨‍💻 Author

**Medical Database Analysis Using Excel**

A healthcare data analytics project demonstrating data cleaning, statistical analysis, and dashboard development using Microsoft Excel
