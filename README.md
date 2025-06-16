# 🩺 Diabetes-Exploratory-Analysis

📊 **Exploratory Data Analysis (EDA) on Diabetes Health Indicators**  
Dataset: Behavioral Risk Factor Surveillance System (BRFSS 2015)

---

## 🔍 Project Overview

This project aims to explore and understand key health indicators associated with diabetes using the BRFSS 2015 dataset, which includes over 250,000 responses from individuals across the United States.

---

## 🧠 Objectives

- Identify correlations between health behaviors and diabetes occurrence
- Visualize health patterns using univariate and bivariate analysis
- Clean and categorize the data for better interpretation
- Derive insights that can support preventive healthcare strategies

---

## 📁 Dataset Description

- 📦 **Source**: [CDC BRFSS 2015 Public Dataset](https://www.cdc.gov/brfss/index.html)
- 🧮 **Total Rows**: 253,680
- 🧬 **Columns**: 22 health indicators such as:
  - `Diabetic`, `High_BP`, `BMI`, `Smoker`, `Physical_Health`, `Income`, `Education`, etc.

---

## 🧹 Data Cleaning Steps

- Removed duplicates
- Renamed columns for clarity
- Converted categorical features (`Sex`, `Education`, `Income`) to proper types
- Checked for null values (none in this dataset)

---

## 📊 Exploratory Data Analysis

### ✅ Univariate Analysis
- BMI Distribution
- Mental Health Days (Boxplot)
- Diabetes Prevalence

### ✅ Bivariate Analysis
- Diabetes vs BMI
- Diabetes vs Smoking
- Diabetes vs Alcohol Consumption

### ✅ Correlation Heatmap

### Correlation Matrix
![Correlation Matrix](images/correlation_matrix.png)

### BMI Distribution
![BMI Distribution](images/bmi_distribution.png)

## 🔑 Key Insights

- Individuals with higher BMI are more likely to be diabetic
- Smoking and heavy alcohol use are slightly more prevalent among diabetic individuals
- Poor mental and physical health days correlate with higher diabetes rates

---

## 📦 Files in this Repo

| File Name                  | Description                                |
|---------------------------|---------------------------------------------|
| `Diabetes_eda_clean.ipynb`| Main Jupyter Notebook for EDA               |
| `README.md`               | Project documentation                       |
| `requirements.txt`        | Libraries used for analysis *(add this)*    |

---

## 🚀 How to Run

```bash
# Clone this repository
git clone https://github.com/laxlago/Diabetes-Exploratory-Analysis.git

# Install required libraries
pip install -r requirements.txt

# Open the notebook
jupyter notebook Diabetes_eda_clean.ipynb

