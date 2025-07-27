# 🛒 Market Basket Analysis for Retail Sales

## 📌 Introduction

This project involves analyzing retail sales data from a store, provided in the file `factors.csv`. The dataset includes transaction records over a certain period, with the following fields:

- `Order_id`: Unique invoice number for each transaction
- `Product_id`: Unique identifier for each product
- `Product_name`: Name of the product
- `Department_id`: Unique identifier for each department
- `Department_name`: Name of the department

The aim is to perform **market basket analysis** using association rule mining techniques to uncover frequent itemsets and rules that help understand customer purchasing behavior.

---

## 🎯 Project Goals

The project is divided into two main parts:

### Part A: Global Store Analysis

1. **Frequently Bought Together Products**  
   Identify pairs of products that are often purchased together across all orders.  
   Metrics:
   - **Support**: Frequency of the product pair across all orders  
   - **Confidence**: Likelihood of buying product B given that product A was bought  

2. **Frequently Bought Together Departments**  
   Identify combinations of departments whose products are often found together in the same cart.  
   Metrics:
   - **Support**
   - **Confidence**

### Part B: Department-Specific Analysis

After the store decides to manage each department independently, we provide department-level insights:

- **Product Association Within Each Department**  
  For each department, find frequently co-purchased products.  
  - Minimum support threshold: **0.003** (0.3%)  
  - Minimum confidence threshold: **0.25** (25%)

---

This analysis helps the business understand customer buying patterns, improve product placement, and inform department-level marketing and bundling strategies.
s