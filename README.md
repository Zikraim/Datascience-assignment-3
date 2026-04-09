# Datascience-assignment-3
#  Titanic Data Analysis & Custom Dataset (Pandas Project)

##  Project Overview

This project focuses on building strong foundational skills in **data analysis using Python and pandas**. It consists of two main parts:

1. Creating a custom dataset from scratch
2. Performing real-world data analysis on the Titanic dataset

The goal is to demonstrate data handling, cleaning, analysis, and extracting meaningful insights.

---

##  Part 1: Custom Dataset Creation

A dataset was created using a Python dictionary with the following requirements:

* 5 features (columns)
* 15 records (rows)
* Custom index labels
This step demonstrates the ability to **construct structured data manually** using pandas.

---

## 🚢 Part 2: Titanic Dataset Analysis

Dataset used: `train.csv`

---

## 🔍 Step 1: Data Exploration

Basic exploration techniques were applied:

* `.head()` → Preview first rows
* `.info()` → Understand data types and missing values
* `.describe()` → Statistical summary

---

## 🧹 Step 2: Data Cleaning

Handled missing values and improved data quality:

* Filled missing **Age** values using median
* Filled missing **Embarked** values using mode
* Dropped the **Cabin** column due to excessive missing data
* Removed duplicate rows

✔ Ensured dataset contains no missing values after cleaning

---

## 📊 Step 3: Data Analysis

Used `groupby()` to analyze patterns:

* Survival rate by gender
* Survival rate by passenger class
* Average age per class
* Survival rate by age groups (without adding a new column)

---

## 🔎 Step 4: Data Filtering

Extracted meaningful subsets:

* Female passengers who survived
* Children who survived
* First-class passengers with high survival rates

---

## 🧠 Step 5: Key Insights

### ✔ Who was more likely to survive?

Females had a significantly higher survival rate than males.

### ✔ Did class affect survival?

Yes. First-class passengers had the highest survival rate, while third-class had the lowest.

### ✔ Were children prioritized?

Yes. Children showed higher survival rates compared to adults.

### ✔ Highest survival combination

Female passengers in first class had the highest survival probability.

---

## 🛠️ Technologies Used

* Python
* pandas

---

## 📁 Project Structure

```
project/
│
├── train.csv
├── analysis.ipynb   # Main notebook
└── README.md
```

---

## ✅ Conclusion

This project highlights the importance of:

* Data cleaning before analysis
* Using pandas for efficient data manipulation
* Extracting insights from real-world datasets

It builds a strong foundation for more advanced data science and machine learning tasks.


