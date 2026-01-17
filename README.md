# Practical_Data_Aggregation
**GitHub Description (≤350 characters):**  This project demonstrates data aggregation in data mining using Python and Pandas. It covers basic aggregation (sum, mean, count, min, max), multi-level grouping, time-based aggregation (monthly, quarterly, yearly), and spatial aggregation by region and city with a sample dataset.

# Data Aggregation in Data Mining (Time & Spatial Aggregation)

## 📌 Overview

This project demonstrates **Data Aggregation** concepts in **Data Mining** using **Python and Pandas**. It explains how raw data can be summarized and grouped to extract meaningful insights using different aggregation techniques.

The project covers:

* Basic aggregation functions
* Multi-level aggregation
* Time-based aggregation
* Spatial aggregation

---

## 🎯 Objectives

* Understand the concept of data aggregation
* Implement different types of aggregation in Python
* Perform **time aggregation** (monthly, quarterly, yearly)
* Perform **spatial aggregation** (region-wise and city-wise)

---

## 🛠 Tools & Libraries Used

* Python
* Pandas

---

## 📂 Dataset Description

The dataset contains sales information with the following attributes:

* **Region** – Geographical area (North, South, East, West)
* **City** – City under each region
* **Product** – Product category (A, B, C)
* **Sales** – Sales amount
* **Quantity** – Number of items sold
* **Date** – Date of transaction

---

## 🔹 Types of Aggregation Implemented

### 1️⃣ Basic Aggregation

* Sum of sales by region
* Mean sales and quantity by product
* Count of sales records
* Minimum and maximum sales values

### 2️⃣ Multi-Level Aggregation

* Sales aggregated by **Region and Product**
* Demonstrates hierarchical grouping

---

## ⏱ Time Aggregation

Time-based aggregation is performed using the `Date` column:

* Monthly sales aggregation
* Quarterly sales aggregation
* Yearly sales aggregation

This helps analyze trends over time.

---

## 🌍 Spatial Aggregation

Spatial aggregation is performed using geographical attributes:

* Total sales by region
* Total sales by city
* Combined aggregation by region and city

This helps analyze location-based performance.

---

## 📈 Output

The program prints aggregated results directly in the console.
The spatial aggregation results can also be exported to a CSV file if required.

---

## 🚀 How to Run

1. Install Pandas:

   ```bash
   pip install pandas
   ```
2. Run the Python script:

   ```bash
   python aggregation.py
   ```

---

## 📚 Learning Outcome

* Clear understanding of data aggregation in data mining
* Practical exposure to Pandas `groupby()` and `resample()`
* Ability to analyze data using time and spatial dimensions

---

## 👩‍🎓 Author

**Rimsha Ansari**

---

