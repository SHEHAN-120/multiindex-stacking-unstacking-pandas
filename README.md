# 🏪 Store Sales Analysis with MultiIndexing, Stacking & Unstacking

## 📌 Overview

This project demonstrates how to use **Pandas MultiIndexing**, **stacking**, and **unstacking** to reshape time-series sales data. The data is normalized by store averages to compare relative performance, and the results are visualized with a Seaborn heatmap.

## 📂 Dataset

* **File:** `train.csv`
* **Columns:** `Store`, `Date`, `Sales`, `Customers`, `Open`, etc.

## 🛠 Key Steps

1. **Load dataset** and set a MultiIndex (`Store`, `Date`).
2. **Reshape data** using `.unstack()` to pivot dates or store IDs into columns.
3. **Normalize sales** by dividing each store's sales by its average.
4. **Visualize** relative performance over time with a Seaborn heatmap.

## 🧰 Tools Used

* 🐍 Python
* 📊 Pandas
* 🎨 Seaborn
* 📈 Matplotlib

## 🚀 Output

The output is a **heatmap** where:

* **X-axis:** Dates
* **Y-axis:** Stores
* **Color intensity:** Sales relative to the store's average performance.

This makes it easy to spot high and low sales periods for each store, regardless of their absolute sales volume.
