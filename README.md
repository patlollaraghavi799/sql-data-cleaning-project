# SQL Data Cleaning Project

## 📌 Overview

This project demonstrates the process of cleaning and preparing a real-world dataset using MySQL. The goal was to improve data quality by removing duplicates, standardizing values, handling missing data, correcting data formats, and preparing the dataset for analysis.

---

## 📂 Dataset

- **Dataset:** Layoffs Dataset
- **Database:** MySQL

---

## 🎯 Objectives

- Create a staging table for safe data cleaning
- Identify and remove duplicate records
- Standardize inconsistent values
- Remove unnecessary spaces
- Format date values correctly
- Handle missing and null values
- Delete records with insufficient data
- Prepare a clean dataset for further analysis

---

## 🛠 SQL Concepts Used

- CREATE TABLE
- INSERT INTO
- Common Table Expressions (CTEs)
- Window Functions (`ROW_NUMBER()`)
- UPDATE
- DELETE
- ALTER TABLE
- JOIN
- String Functions (`TRIM()`)
- Date Functions (`STR_TO_DATE()`)

---

## 📈 Data Cleaning Steps

### 1. Created a Staging Table
Copied the original dataset into a staging table to preserve the raw data.

### 2. Removed Duplicate Records
Used the `ROW_NUMBER()` window function to identify duplicate rows and removed them.

### 3. Standardized Data
- Removed extra spaces from company names
- Standardized industry names (e.g., Crypto)
- Corrected country names
- Converted dates into SQL DATE format

### 4. Handled Missing Values
- Replaced blank industry values where possible using self joins
- Removed records containing insufficient information

### 5. Final Cleanup
Dropped temporary columns used during the cleaning process

## 📚 What I Learned

Through this project, I gained hands-on experience with:

- SQL data cleaning techniques
- Window functions
- Data standardization
- Handling missing values
- Working with dates in SQL
- Preparing datasets for analysis

---

## 🙏 Acknowledgement

This project was completed as part of my SQL learning journey by following the SQL Data Cleaning Project from **Alex The Analyst**. The project was recreated and documented by me for learning and practice purposes.

---

## 👩‍💻 Author

**Raghavi Patlolla**
