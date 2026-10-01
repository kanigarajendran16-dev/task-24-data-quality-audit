# Task 24 - Data Quality Audit

## Veda Technology Data Analytics Internship

This project focuses on performing a complete Data Quality Audit using Python and Pandas.

The dataset is checked for missing values, duplicate records, range violations, and consistency issues. The identified issues are quantified, logged, cleaned, and visualized through interactive charts and a live dashboard.

---

## 👨‍💻 Student Details

**Name:** R. Kaniga  
**Program:** B.Tech - Artificial Intelligence and Data Science  
**Department:** Artificial Intelligence and Data Science  
**College:** Muthayammal Engineering College  
**Academic Period:** 2025 - 2029  
**Internship:** Veda Technology  
**Task:** Task 24 - Data Quality Audit  
**Platform:** Google Colab  

---

## 🎯 Objective

The main objective of this project is to audit a dataset and identify common data quality problems.

The project focuses on:

- Missing value identification
- Duplicate record detection
- Range validation
- Data consistency validation
- Issue quantification
- Issue logging
- Data cleaning
- Quality checklist creation
- Data visualization
- Interactive dashboard creation

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Plotly
- OpenPyXL
- Google Colab
- HTML
- Excel

---

## 📊 Dataset

A Retail Sales dataset is used for the Data Quality Audit.

The dataset contains fields such as:

- Order ID
- Order Date
- Region
- Category
- Product
- Quantity
- Sales

The dataset contains intentionally introduced quality issues so that the audit process can identify and demonstrate different types of data problems.

---

## 🔍 Data Quality Checks

### 1. Missing Value Check

The dataset is checked for NULL or missing values.

The following metrics are calculated:

- Missing count
- Missing percentage
- Affected columns

---

### 2. Duplicate Check

Duplicate records are identified using Pandas.

The following metrics are calculated:

- Total records
- Duplicate records
- Duplicate percentage

---

### 3. Range Validation

Business validation rules are applied.

Examples:

- Quantity must be greater than 0
- Sales must be greater than 0

Invalid values are identified and logged.

---

### 4. Consistency Validation

Text fields are checked for inconsistent values.

Examples:

```text
South
south
 SOUTH
