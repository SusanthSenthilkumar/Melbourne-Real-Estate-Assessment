# Melbourne Real Estate Analysis

## 📊 Dashboard Preview

![Dashboard](dashboard.png)

## 🧩 Data Model View

![Model](model_view.png)

## 📌 Project Overview

This project analyzes Melbourne housing data using **SQL, Python, and Power BI** to uncover pricing trends, data quality issues, and suburb-level insights.

---

## 🛠 Tools & Technologies

* SQL Server (Data querying)
* Python (Pandas, NumPy for data processing)
* Power BI (Data visualization)

---

## 📂 Project Structure

* **PowerBI/** → Power BI dashboard file (.pbix)
* **SQL/** → SQL queries and solutions
* **Python/** → Data cleaning & feature engineering notebook
* **Dataset/** → Source dataset used for analysis

---

## ✅ Tasks Completed

### 🔹 Task 1: Data Quality Management

* Handled missing values using **median imputation**
* Removed outliers using **IQR method**
* Ensured data consistency for analysis

---

### 🔹 Task 2: Feature Engineering (Property Level)

Created new features:

* **Price per Room** → price / rooms
* **Price per Land Size** → price / landsize
* **Property Age** → 2017 - yearBuilt

These features help in better understanding property value.

---

### 🔹 Task 3: Feature Engineering (Suburb Level)

* Grouped data by suburb
* Calculated:

  * Average price
  * Average building area
* Created:

  * **Price to Building Area Ratio**

This helps compare property value across suburbs.

---

## 📈 Key Insights

* Property prices vary significantly by suburb
* Larger land size does not always mean higher value
* Older properties show varied pricing trends

---

## ▶️ How to Use

1. Open **Power BI file** to view dashboard
2. Run **Python notebook** for data processing
3. Execute **SQL queries** for database analysis

---

## 👤 Author

Susanth Senthilkumar
