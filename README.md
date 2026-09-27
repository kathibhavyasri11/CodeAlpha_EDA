# CodeAlpha – Task 2: Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project is part of the **CodeAlpha Data Analytics Internship – Task 2**.

The objective of this project is to perform **Exploratory Data Analysis (EDA)** on a sales dataset using Python and Google Colab.

EDA helps in understanding the structure of the dataset, identifying patterns, checking data quality, and discovering relationships between different variables.

---

## 🎯 Objectives

- Understand the dataset structure.
- Explore the variables and their data types.
- Check for missing values.
- Identify duplicate records.
- Generate statistical summaries.
- Analyze numerical variables.
- Identify potential outliers.
- Study relationships between variables.
- Create visualizations to understand the dataset.

---

## 📂 Dataset

The project uses a sales dataset containing information about products, sales quantities, prices, regions, and total sales.

### Dataset Columns

| Column | Description |
|---|---|
| `Date` | Date of the sales transaction |
| `Product` | Product name |
| `Category` | Product category |
| `Quantity` | Number of units sold |
| `Unit_Price` | Price per unit |
| `Region` | Sales region |
| `Total_Sales` | Total sales amount |

---

## 🛠️ Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Exploratory Data Analysis
- Data Visualization

---

## 🔍 EDA Process

The following steps were performed during the analysis:

### 1. Data Loading

The dataset was loaded into Google Colab using Pandas.

### 2. Data Exploration

The dataset was explored to understand:

- Number of rows and columns
- Column names
- Data types
- Sample records
- Unique values

### 3. Data Quality Checks

The dataset was checked for:

- Missing values
- Duplicate records
- Data type consistency

### 4. Statistical Analysis

Descriptive statistics were used to understand numerical variables such as:

- Quantity
- Unit Price
- Total Sales

### 5. Data Visualization

Visualizations were created to understand patterns and distributions in the dataset.

The analysis includes visual techniques such as:

- Histograms
- Box plots
- Correlation analysis

### 6. Outlier Analysis

Box plots were used to identify potentially unusual values in numerical variables.

### 7. Correlation Analysis

Correlation analysis was used to examine relationships between numerical variables.

---

## 🧮 Total Sales

The total sales value is calculated using:

```text
Total Sales = Quantity × Unit Price
