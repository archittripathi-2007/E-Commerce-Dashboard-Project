# E-Commerce-Dashboard-Project
# 📊 E-Commerce Sales & Profit Dashboard

A lightweight, command-line Python application built with `pandas` to analyze e-commerce sales datasets, preview records, and generate a summary of key business metrics (KPIs).

---

## ✨ Features

- **Interactive Dataset Selection:** Choose from available CSV sales files directly in the terminal.
- **Data Preview:** Specify the exact number of rows (`n`) you want to inspect from the top of the dataset.
- **Automated KPI Calculation:**
  - **Total Orders:** Total count of transactions/rows.
  - **Total Revenue:** Cumulative sales value formatted in INR.
  - **Total Profit:** Net profit generated across all orders in INR.
  - **Profit Margin:** Overall profitability percentage `(Total Profit / Total Revenue) * 100`.
  - **Top Category:** Identifies the highest-grossing product category.
- **Error Handling:** Gracefully handles missing files (`FileNotFoundError`) and invalid numeric inputs (`ValueError`).

---

## 📋 Prerequisites

- **Python 3.7+**
- **pandas** library

Install the required dependency using `pip`:

```bash
pip install pandas
