# Coffee Sales Analysis: Exploratory Data Analysis (EDA)

This project presents an exploratory data analysis of coffee shop sales over approximately one year, using Python (Pandas, Matplotlib, and Seaborn). The goal is to understand consumption patterns, product performance, and temporal seasonality, generating practical insights for business decisions.

---

## About the Dataset

The dataset used is publicly available on Kaggle:  
**Coffee Sales – Kaggle Dataset**  
https://www.kaggle.com/datasets/ihelon/coffee-sales

It contains 3,636 sales records from March/2024 to March/2025, with the following main columns:

- `date` – date of the sale  
- `datetime` – timestamp of the sale  
- `cash_type` – payment method  
- `money` – transaction value  
- `coffee_name` – type of coffee sold  

The structure allows both product-level and temporal analyses.

---

## Objectives

This analysis aims to answer questions such as:

- Which products have the highest sales volume and revenue?  
- How do sales vary over time (daily, weekly, monthly)?  
- Are there any seasonal or recurring patterns?  
- How does the average ticket price differ between coffee types?  
- Which days of the week perform best or worst?  
- What insights can support strategic decision-making?  

---

## Key Findings

### Product Analysis
- The products with the highest sales volume were:  
  - Americano with Milk (824)  
  - Latte (782)  
  - Americano (578)  

- In terms of total revenue, the top items were:  
  - Latte (R$ 27,866.30)  
  - Americano with Milk (R$ 25,269.12)  
  - Cappuccino (R$ 18,034.14)  

- For average ticket price, the highlights were:  
  - Hot Chocolate (R$ 36.07)  
  - Cappuccino (R$ 36.00)  
  - Cocoa (R$ 35.71)  

### Temporal Analysis
- The highest monthly revenue was recorded in:  
  - October 2024 (R$ 13,891.16)  
  - February 2025 (R$ 13,215.48)  

- The lowest month was January 2025 (R$ 6,398.86).  
- Among weekdays, Tuesday had the highest total revenue.

---

## Business Insights

Based on the analysis, some potential actions include:

- Focusing marketing campaigns on historically stronger months.  
- Using Espresso as an entry-level item to attract new customers.  
- Creating discounts or combo deals on traditionally strong days, such as Tuesdays.  
- Planning specific actions to increase activity on Sundays.  
- Automating monthly reports for continuous performance monitoring.  

---

## Next Steps

- Incorporate cost data to analyze product margins.  
- Explore customer segmentation using payment information.  
- Develop a simple sales forecasting model.  
- Automate monthly reports with Python.

---

## Tools Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab
