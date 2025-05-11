
# 🏥 Hospital Data Analysis — BI & Data Mining Project

This repository contains a full end-to-end **healthcare analytics project** focused on hospital patient recovery analysis using **Excel**, **Tableau**, and **Weka**. The project is part of the **Business Intelligence (CST3340)** module at the University of Wolverhampton.

---

## 📄 Project Title
**Hospital Patient Recovery Analysis using Tableau and Weka**

### 👤 Author:
**Atiqahmed Hanifmohmed Rathod**  


---

## 🎯 Project Overview

This case study analyzes a dataset of **851 patient records** with 11 attributes related to patient demographics, medical conditions, and recovery status. The objective is to explore insights that can support hospital decision-making and enhance recovery outcomes.

---

## 🛠 Tools & Technologies

- **Microsoft Excel** – Data cleaning, normalization, and preprocessing
- **Tableau** – Interactive dashboards and KPI visualizations
- **Weka** – Data mining using the Apriori algorithm

---

## 📊 Key Project Steps

### 1. **Data Cleaning**
- Removed patient IDs to preserve privacy
- Grouped continuous attributes (Age, BP, Heart Rate, Length of Stay) into categories
- Ensured consistency in labels (e.g., "Recovered" status)

### 2. **Tableau Visualizations**
Created interactive charts to explore:
- Recovery by Region & Age
- Recovery by Gender & Treatment
- Heatmaps of treatment effectiveness
- KPI Dashboards and calculated fields
- LOD expressions and parameterized visuals

### 3. **Weka Data Mining**
- Used the **Apriori algorithm** for association rule mining
- Ran 3 iterations with varying confidence/support thresholds
- Balanced the dataset using **SMOTE** to improve fairness
- Generated strong rules linking treatment type, insurance, and diagnosis to recovery status

---

## 🔍 Key Insights

- **Age and Region** are major factors influencing recovery outcomes.
- **Treatment Type** like Surgery showed higher recovery rates in some demographics.
- Insurance and length of stay revealed strong associations with outcomes in Apriori.
- Tableau dashboards highlighted actionable patterns across demographics.

---

## 📂 Files Included

- `M00836914_cst3340.docx` – Full report with analysis, screenshots, and discussions
- (Optional) `Cleaned_Hospital_Data.csv` – Ready-to-use dataset for Tableau and Weka
- (Optional) `.arff` files – Formatted files for Weka analysis
- Tableau workbook (if available)

---

## ✅ Conclusion

This project demonstrates a complete Business Intelligence pipeline:
1. **Data Cleaning** using Excel
2. **Visual Analysis** using Tableau
3. **Pattern Mining** using Weka

It provides practical insights into healthcare operations and shows how BI tools can support evidence-based decision-making in hospitals.
