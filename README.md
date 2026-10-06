# 🏥 Hospital Management – SQL Project

## 📌 Project Overview

This project demonstrates SQL skills through the analysis of a **Hospital Management dataset**.

The project focuses on analyzing hospital operations, patient volumes, medical expenses, departments, doctors, and patient stay duration using SQL.

The queries range from basic aggregation and filtering to advanced SQL concepts such as **CTEs, Window Functions, DENSE_RANK, JOIN-style analytical logic, date calculations, GROUP BY, and aggregate functions**.

## 🗂️ Database Overview

The project uses a **Hospital Management database** containing hospital-related information such as:

- Hospital Name
- Department
- Location
- Patient Count
- Doctors Count
- Medical Expenses
- Admission Date
- Discharge Date

The database is created as `HOSPITAL_MANAGEMENT`, with the analysis performed on the `HOSPITAL_DATA` table.

## 🔍 Analysis Performed

The project answers several real-world hospital management questions.

### 1. Patient Analysis

- Calculate the total number of patients across hospitals.
- Identify hospitals with higher patient volumes.
- Calculate total patients treated by city.
- Identify departments with the lowest number of patients.

### 2. Doctor & Department Analysis

- Calculate the average number of doctors available per hospital.
- Identify the top departments based on patient volume.
- Calculate the average length of patient stay by department.

### 3. Medical Expense Analysis

- Identify the hospital with the highest medical expenses.
- Calculate average medical expenses per day for each hospital.
- Generate a monthly medical expenses report.

### 4. Patient Stay Analysis

- Identify the hospital associated with the longest patient stay.
- Calculate the average number of days patients spend in each department.
- Analyze admission and discharge dates using `DATEDIFF()`.

## 🛠️ SQL Concepts Used

This project demonstrates:

- `SELECT`
- `WHERE`
- `GROUP BY`
- `ORDER BY`
- `TOP`
- `SUM()`
- `AVG()`
- `MAX()`
- `DENSE_RANK()`
- `WITH` / CTE
- Window Functions
- `DATEDIFF()`
- `FORMAT()`
- `ROUND()`
- `CAST()`
- `NULLIF()`
- Aggregate Functions
- Date-based analysis
- Data aggregation
- Ranking and analytical queries

## 💡 Business Insights

The analysis can help hospital management understand:

- 👥 Patient volume across hospitals and cities
- 👨‍⚕️ Doctor availability
- 🏥 Department-wise patient load
- 💰 Medical expenses and cost trends
- 📅 Monthly medical expenditure
- ⏱️ Patient length of stay
- 📊 Departments with high or low patient volumes
- 🏨 Hospital-level operational performance

## 📁 Project Structure

```text
Hospital-Management-SQL/
│
├── HOSPTIAL NEW PROJECT.SQL
└── README.md
```

## 🎯 Project Objective

The main objective of this project is to demonstrate practical **SQL data analysis and problem-solving skills** by converting hospital-related business questions into SQL queries.

This project showcases the ability to work with **aggregations, date calculations, CTEs, window functions, ranking, and business-oriented analytical queries**.

## 🚀 Key Learning

Through this project, I practiced using SQL to transform raw hospital data into meaningful operational insights that can support **hospital performance monitoring and management decision-making**.
