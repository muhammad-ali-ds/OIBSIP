# 🧹 Data Cleaning and Preprocessing

## 📌 Project Overview

This project focuses on cleaning and preprocessing a messy customer dataset to improve its quality and prepare it for data analysis. The dataset contained missing values, duplicate records, inconsistent formatting, incorrect data types, and outliers. Various data cleaning techniques were applied to transform it into a clean and reliable dataset.

---

## 🎯 Objectives

- Identify data quality issues.
- Handle missing values.
- Remove duplicate records.
- Correct inconsistent data entries.
- Convert columns to appropriate data types.
- Detect and handle outliers.
- Export a clean dataset ready for analysis.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains customer information, including:

- Customer ID
- Age
- Gender
- City
- Signup Date
- Last Purchase Date
- Purchase Amount
- Feedback Score
- Country

---

## 📋 Data Quality Issues Identified

### Completeness Issues
- Missing values in multiple columns.
- Missing customer information.

### Validity Issues
- Incorrect data types.
- Negative values in Purchase Amount.
- Age values stored as text (e.g., "25 years").

### Consistency Issues
- Inconsistent values in Gender.
- Different capitalization in City and Country names.

### Accuracy Issues
- Outliers detected in Purchase Amount and Age.

### Uniqueness Issues
- Duplicate rows.
- Duplicate Customer IDs.

---

## 🔧 Data Cleaning Steps

- Loaded and inspected the dataset.
- Generated a Data Quality Report.
- Handled missing values using appropriate techniques.
- Removed duplicate records.
- Standardized categorical values.
- Corrected data types.
- Detected and handled outliers.
- Compared the dataset before and after cleaning.
- Exported the cleaned dataset as a new CSV file.

---

## 📊 Key Results

- Missing values handled successfully.
- Duplicate rows removed.
- Data types corrected.
- Inconsistent values standardized.
- Outliers treated.
- Clean dataset exported for future analysis.

---

## 📁 Repository Structure

```
DataAnalytics-L1-DataCleaning/
│
├── Data_Cleaning.ipynb
├── messy_customer_data.csv
├── cleaned_customers.csv
├── README.md
└── images/
```

---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone https://github.com/muhammad-ali-ds/OIBSIP.git
```

2. Navigate to the project folder.

```bash
cd DataAnalytics-L1-DataCleaning
```

3. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn
```

4. Open the Jupyter Notebook.

```bash
jupyter notebook
```

5. Run all cells to reproduce the cleaning process.

---

## 📌 Output

The project generates:

- Cleaned dataset (`cleaned_customers.csv`)
- Data Quality Report
- Before vs After Summary
- Data Cleaning Notebook

---

## 👨‍💻 Author

**Muhammad Ali**

GitHub: https://github.com/muhammad-ali-ds

LinkedIn: https://www.linkedin.com/in/muhammad-ali-175691383

---

## ⭐ Project Information

**Track:** Data Analytics

**Level:** Level 1

**Task:** Task 3 – Data Cleaning

---
