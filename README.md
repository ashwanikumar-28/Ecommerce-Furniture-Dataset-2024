# E-commerce Furniture Dataset 2024

##  Project Overview

This project focuses on analyzing and predicting online furniture sales using data collected from an e-commerce platform (AliExpress).
The goal is to understand how **price, shipping tags, and product titles** influence the number of items sold and to build machine learning models for sales prediction.

This project is created as part of an **internship / beginner-level data analytics & machine learning project**.

---

##  Objectives

* Analyze sales patterns of furniture products
* Understand the relationship between price and number of items sold
* Study the impact of free shipping on sales
* Predict the number of units sold using machine learning models

---

##  Dataset Information

* **File Name:** `ecommerce furniture dataset 2024.csv`
* **Total Records:** 2000
* **Columns:**

  * `productTitle` – Product name/title
  * `originalPrice` – Original price (mostly missing, dropped)
  * `price` – Current selling price
  * `sold` – Number of units sold (Target variable)
  * `tagText` – Shipping information (Free shipping / Others)

---

##  Tools & Technologies

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* VS Code
* GitHub

---

##  Exploratory Data Analysis (EDA)

* Distribution of product prices
* Distribution of items sold
* Relationship between price and sales
* Impact of shipping tags on sales

---

##  Feature Engineering

* Cleaned price column by removing currency symbols
* Encoded shipping tags (`Free shipping` vs `others`)
* Converted `productTitle` text into numerical features using **TF-IDF Vectorization**

---

##  Machine Learning Models

Two regression models were trained:

1. **Linear Regression**
2. **Random Forest Regressor**

---

##  Model Evaluation

* **Evaluation Metrics:**

  * Mean Squared Error (MSE)
  * R² Score
* Random Forest performed better due to its ability to handle non-linear relationships.

---

##  How to Run the Project

### 1️⃣ Install Required Libraries

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 2️⃣ Run the Python Script

```
python main.py
```

---

## Project Structure

```
Ecommerce-Furniture-Dataset-2024/
│
├── ecommerce furniture dataset 2024.csv
├── main.py
├── Ecommerce_Furniture_Dataset_2024_Project_Report.pdf
└── README.md
```

---

##  Conclusion

This project demonstrates how data analytics and machine learning techniques can be applied to real-world e-commerce data.
The insights from this analysis can help businesses make better **pricing, marketing, and logistics decisions**.

