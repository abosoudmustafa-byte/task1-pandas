# 📊 Sales Data Analysis Project

## 📌 Project Overview
This project demonstrates an end-to-end sales data analysis workflow using Python.  
The analysis includes data cleaning, feature engineering, aggregation, and visualization.

The goal of this project is to practice fundamental data analysis skills using:
- Pandas
- NumPy
- Matplotlib

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📂 Dataset Description
The dataset contains sales transaction data including:

- Order ID
- Customer Name
- City
- Product
- Price
- Quantity
- Order Date

---

## 🧹 Data Cleaning Steps
- Filled missing values in:
  - `price` using median
  - `quantity` using median
  - `customer_name` using "Unknown"
  - `city` using mode
- Checked for remaining null values

---

## ⚙️ Feature Engineering
- Created a new column: `total_amount = price × quantity`
- Extracted month from order_date

---

## 📈 Data Analysis
- Total quantity sold
- Highest sales transaction
- Monthly sales aggregation
- Sales by product
- Sales distribution by city

---

## 📊 Visualizations
The project includes:

- Line chart → Monthly sales
- Bar chart → Total sales by product
- Pie chart → Sales distribution by city

---

## 🚀 How to Run the Project
1. Clone the repository
2. Open the notebook in Jupyter
3. Run all cells

---

## 🎯 Skills Demonstrated
- Data Cleaning
- Handling Missing Values
- GroupBy & Aggregation
- Data Visualization
- Feature Engineering

---

## 👨‍💻 Author
Your Name Here
