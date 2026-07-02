# 🧹 Data Cleaning & Preparation

## 📌 Project Overview

This project was completed as **Project 1** during my **Data Analytics Internship at DecodeLabs**.

The objective was to clean and prepare a raw e-commerce dataset by identifying missing values, checking for duplicate records, validating data formats, and preparing the dataset for further analysis.

---

## 🎯 Objectives

- Load the raw dataset
- Inspect the dataset structure
- Identify missing values
- Handle missing values
- Check for duplicate records
- Validate categorical data
- Verify numerical calculations
- Save the cleaned dataset

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Visual Studio Code

---

## 📂 Project Structure

```
DataCleaningProject/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   └── data_cleaning.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📊 Dataset Summary

- Rows: **1200**
- Columns: **14**

### Features

- OrderID
- Date
- CustomerID
- Product
- Quantity
- UnitPrice
- ShippingAddress
- PaymentMethod
- OrderStatus
- TrackingNumber
- ItemsInCart
- CouponCode
- ReferralSource
- TotalPrice

---

## 🔍 Data Cleaning Process

### 1. Dataset Inspection

- Checked dataset dimensions
- Verified data types
- Reviewed summary statistics

### 2. Missing Values

- Identified missing values in the `CouponCode` column.
- Replaced missing values with **"No Coupon"** based on business context.

### 3. Duplicate Records

- Checked for duplicate rows.
- No duplicate records were found.

### 4. Data Validation

Validated the following columns:

- PaymentMethod
- OrderStatus
- ReferralSource

All values were already consistent.

### 5. Total Price Validation

Verified that:

```
TotalPrice = Quantity × UnitPrice
```

Direct comparison initially showed minor mismatches due to floating-point precision.

After rounding to two decimal places, all calculations were successfully validated.

---

## ✅ Final Results

- Missing values handled
- Duplicate records checked
- Data types validated
- Categorical values verified
- Total price calculations validated
- Clean dataset exported successfully

---

## 📁 Output

- Cleaned_Dataset.xlsx

---

## 🚀 Learning Outcomes

Through this project, I learned:

- Data inspection using Pandas
- Handling missing values
- Data validation techniques
- Understanding floating-point precision
- Preparing datasets for analysis
- Documenting the data cleaning workflow

---

## 👨‍💻 Author

Dileep Reddy Pilli

Data Analytics Intern

DecodeLabs