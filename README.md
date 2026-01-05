
## 📌 Retail Sales Analytics & Customer Segmentation (Python, Machine Learning)

### 📂 Project Type: Data Analytics | Machine Learning | Unsupervised Learning

### 🛍 Domain: Retail | E-Commerce | Business Analytics

---

### 🧾 Project Overview

This project focuses on analyzing **retail transaction data** to uncover **sales trends, customer purchasing behavior, and high-value customer segments**.

Using Python, the dataset was **cleaned, transformed, and analyzed** to:

* study **monthly and seasonal sales**
* calculate **Customer Lifetime Value (CLV)**
* create **customer–category purchase frequency matrix**
* perform **K-Means clustering**
* generate **visual business insights**

The dataset used is from **Kaggle – Retail Store Sales (Dirty Dataset)**.

---

## 🎯 Objectives

✔ Clean and preprocess raw retail transaction data
✔ Perform Exploratory Data Analysis (EDA)
✔ Identify **top products and categories**
✔ Analyze **monthly and seasonal sales trends**
✔ Calculate **Customer Lifetime Value (CLV)**
✔ Perform **customer segmentation using K-Means**
✔ Visualize insights using charts and heatmaps

---

## 🛠️ Tools & Technologies

| Area             | Tools                  |
| ---------------- | ---------------------- |
| Programming      | Python                 |
| Data Handling    | Pandas, NumPy          |
| Visualization    | Matplotlib, Seaborn    |
| Machine Learning | Scikit-learn           |
| Clustering       | K-Means                |
| Notebook         | Jupyter / Google Colab |

---

## 📊 Dataset Description

The dataset contains:

* Customer ID
* Transaction ID
* Product Category
* Quantity purchased
* Price per unit
* Total spending
* Date of transaction
* Location / store information
* Payment method

The dataset originally contained **missing values, duplicates, and inconsistent text** which were processed during data cleaning.

---

## 🧹 Data Cleaning Performed

* handled missing values
* removed duplicates
* converted date column to datetime format
* standardized text values
* derived:

  * `TotalAmount`
  * `Month`
  * `Day`
* filtered invalid or negative quantities

---

## 📈 Exploratory Data Analysis (EDA)

Key questions explored:

* What are the **top-selling products**?
* Which **categories generate the most revenue**?
* Which **customers are most valuable**?
* Which **months show maximum sales?**
* Which **locations/stores perform best?**
* What **payment methods are most used?**

---

## 💰 Customer Lifetime Value (CLV)

CLV was computed using:

```
CLV = total revenue generated per customer
```

This was achieved using:

```python
clv = df.groupby('CustomerID')['TotalAmount'].sum()
```

---

## 🤖 Machine Learning — K-Means Clustering

Two segmentation approaches were implemented:

### ✔ CLV-based customer segmentation

Customers grouped into:

* high value
* medium value
* low value

### ✔ Category-behavior segmentation

Created **Customer vs Category frequency matrix** and applied clustering to identify:

* electronics-focused buyers
* clothing buyers
* multi-category shoppers
* low-activity customers

---

## 📉 Visualizations Created

* monthly revenue trend line chart
* category-wise bar charts
* heatmap of category behavior per cluster
* scatterplot of CLV clusters
* payment method distribution

---

## 🚀 Business Insights

📌 High revenue months show festival-season demand
📌 20% customers contribute majority of revenue (Pareto pattern)
📌 Specific categories dominate in specific months
📌 Customer clusters reveal **distinct purchase behaviors**
📌 Results support:

* targeted promotions
* inventory planning
* loyalty campaign design

---

## 🧭 How to Run the Project

1. Clone the repo
2. Install required libraries

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open notebook

```
jupyter notebook
```

4. Load dataset file
5. Run cells step-by-step

---

## 📌 Future Enhancements

🔹 Dashboard using Power BI / Tableau
🔹 Market basket analysis (Apriori)
🔹 Time-series forecasting (ARIMA/LSTM)
🔹 Web app using Streamlit / Flask

---

## 🧑‍💻 Author

Anishka Singh
singhanishka517@gmail.com
🎓 Data Analyst / Data Science Enthusiast
📬 Open for internships & projects
