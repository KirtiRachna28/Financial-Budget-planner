# 📊 Financial Budget Planner (Excel Project)

## 📌 Overview

The **Financial Budget Planner** is an Excel-based project designed to help users track income, expenses, and savings efficiently. It provides meaningful insights through data analysis and interactive dashboards using Excel features like Pivot Tables, charts,slicers, and conditional formatting.

---

## 🎯 Objectives

* Analyze **monthly income vs expenses**
* Understand **category-wise spending**
* Calculate **savings**
* Build an interactive **budget dashboard**
* Visualize **expense trends over time**

---

## 📂 Dataset Structure

| Column Name    | Description                                    |
| -------------- | ---------------------------------------------- |
| Date           | Transaction date                               |
| Category       | Type of transaction (Food, Rent, Salary, etc.) |
| Income         | Amount received                                |
| Expense        | Amount spent                                   |
| Payment Method | Cash, Card, UPI, etc.                          |
| Description    | Transaction details                            |
| Balance        | Running balance                                |

---

## ⚙️ Excel Features Used

### 🔹 SUMIFS

Used to calculate actual based on conditions
Example:

```excel
=SUMIFS(Financial_Data!D:D,Financial_Data!B:B,[@Category])
```

---

### 🔹 Pivot Tables

Used for:

* Monthly summaries
* Category-wise expense analysis
* Dynamic reporting

---

### 🔹 Charts

* 📊 Column Chart → Income vs Expense
* 🥧 Pie Chart → Category breakdown
* 📈 Line Chart → Expense trends
*▁▃▅▇ Area Chart - Budget Vs Actual Comparison

---

### 🔹 Conditional Formatting

* Tracks savings visually
* Budget indicators (Red = Over budget, Green = Under budget)

---

## 📊 Dashboard Features

### 🔹 KPI Cards

* Total Income
* Total Expense
* Total Savings
* Budget Variance

### 🔹 Visualizations

* Monthly Income vs Expense
* Category-wise Expense Distribution
* Expense Trend Chart
* Budget Vs Actual Chart

### 🔹 Filters

* Slicers for:

  * Year
  * Month
  * Category
  * Payment Method

---

## 🧮 Key Calculations

### 🔹 Savings

```excel
=Total Income - Total Expense
```

### 🔹 Balance

```excel
= Income - Expense
```

---

## 🏗️ Steps to Build

1. Create dataset with required columns
2. Convert data into an Excel Table
3. Add formulas (Balance, Savings)
4. Create Pivot Tables
5. Insert charts from Pivot Tables
6. Design dashboard layout
7. Apply conditional formatting
8. Add slicers for interactivity

---

## ✅ Expected Outcomes

* Clear financial insights
* Better spending control
* Easy savings tracking
* Professional dashboard visualization

---

## 🚀 Future Improvements

* Automate reports using macros
* Add yearly performance summary

---

## 📁 Project Files

* `Financial_Budget_Planner.xlsx`

---

## 🤝 Contributing

Feel free to fork this repository and improve the dashboard or add new features.

---


