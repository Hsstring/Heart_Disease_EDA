# Heart Disease EDA

<p>
 <img src="images/Coronary-heart-disease.jpg">
</p>

---

## 📌 Project Overview

This repository contains a comprehensive **Exploratory Data Analysis** of the **Heart Disease Dataset**, used for cardiovascular health research and analysis.  
The dataset includes demographic, clinical, and diagnostic measurements used to predict the presence of heart disease.

This EDA explores feature distributions, correlations, relationships with the disease outcome, and patterns that may influence prediction models.

---

## 🎯 Objectives

- Perform a detailed **Exploratory Data Analysis**  
- Visualize feature distributions and relationships  
- Identify outliers and important predictors  
- Understand correlations between health indicators  

---

## 📊 Dataset Description

- **Source:** Private Dataset  
- **Type:** Tabular medical dataset in CSV 
- **Rows:** 303 patient records  
- **Target Variable:**  
  - `target`:  
    - `1` → presence of heart disease  
    - `0` → no heart disease  

### Features Description

| Feature | Description |
|--------|-------------|
| age | Patient age |
| sex | Gender (0 = female, 1 = male) |
| cp | Chest pain type (0–3) |
| trestbps | Resting blood pressure (mm Hg) |
| chol | Serum cholesterol (mg/dl) |
| fbs | Fasting blood sugar (>120 mg/dl, 1 = true) |
| restecg | Resting ECG results |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina |
| oldpeak | ST depression induced by exercise |
| slope | Slope of peak exercise ST segment |
| ca | Number of major vessels (0–4) |
| thal | Thalassemia (0–3) |
| target | Heart disease indicator |

### Statistical Overview (From Provided Summary)

- Average age: **~54 years**  
- Average resting BP: **~131 mmHg**  
- Average cholesterol: **~246 mg/dl**  
- Mean max heart rate: **~149 bpm**  
- Heart disease prevalence: **~54%**  

---

## 🔍 Exploratory Data Analysis (EDA)

### 1. Statistical Summary  
- Basic insights into data distribution
- Number of Data and Features
- 

### 2. Missing Value Analysis  
- No missing values detected in this dataset  
- All features are complete and ready for modeling  

### 3. Distribution Analysis  
Histogram plots were used to analyze distributions for:
- age  
- trestbps  
- chol  
- thalach  
- oldpeak  

Findings:
- Cholesterol and oldpeak show skewness/outliers  
- Age distribution is mostly uniform between 40–60  

### 4. Categorical Feature Exploration  
Countplots for categorical variables such as:
- chest pain type (cp)  
- sex  
- thal  
- ca  

Findings:
- Certain chest pain types are strongly associated with heart disease  
- Males are more represented in the dataset  

### 5. Correlation Analysis  
A heatmap visualization highlighted:
- strong positive correlation of **oldpeak**, **exang**, and **ca** with heart disease  
- strong negative correlation of **thalach** with disease presence  
- chest pain type (**cp**) as an important predictor  

### 6. Outlier Detection  
Boxplots revealed:
- high cholesterol outliers  
- BP fluctuations  
- significant ST depression variations (oldpeak)  

These outliers may hold clinical importance and were not removed.

---

## 📈 Example Visualizations

<img src="images/chol vs age .png" width="600"/>

---

## 👤 Author

**Hannah Ahmadzadeh**  
MSc Student in Artificial Intelligence  
Junior Machine Learning Engineer & AI Researcher  

GitHub: https://github.com/Hsstring  
Google Scholar: https://scholar.google.com/citations?user=8pbPFhUAAAAJ&hl=en  
