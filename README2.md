# Coffee Sales Analysis: Revenue Strategy and Demand Patterns (Mar 2024 – Mar 2025)

Exploratory analysis of coffee shop sales data to understand product performance, revenue drivers, and demand patterns over time.

The goal of this project is to transform raw transactional data into **practical business insights** that can support decisions about pricing, promotions, and operational planning.

---

## Dataset

Public dataset available on Kaggle:  
https://www.kaggle.com/datasets/ihelon/coffee-sales

The dataset contains **3,636 transactions between March 2024 and March 2025**, including:

- `date` – date of the sale  
- `datetime` – timestamp of the transaction  
- `cash_type` – payment method  
- `money` – transaction value  
- `coffee_name` – product sold  

---

## Objectives

The analysis focuses on answering a few key business questions:

- Which products generate the most revenue?
- Which products sell the most units?
- Are there clear demand patterns across time?
- Which periods show stronger or weaker performance?
- What actions could improve revenue and customer flow?

---

## Data Preparation

Key preparation steps included:

- Converting date columns to proper datetime format
- Creating time features such as **weekday, hour, and month**
- Checking missing values and payment behavior

An interesting operational insight is that **97.5% of transactions are card payments**, suggesting a highly digital customer base.

---

## Key Visual Insights

### Product Demand

![Sales by coffee type](img/plot1_Vendas%20por%20tipo%20de%20café.png)

The most frequently sold products are:

- Americano with Milk (824)
- Latte (782)
- Americano (578)

These represent the core demand of the coffee shop.

---

### Revenue Drivers

![Revenue by coffee type](img/plot2_Faturamento%20por%20Tipo%20de%20Café.png)

Revenue analysis reveals that **volume and revenue are not always aligned**.

Top revenue contributors:

- Latte — 27,866
- Americano with Milk — 25,269
- Cappuccino — 18,034

Products with slightly lower volume can still contribute strongly to total revenue due to higher prices.

---

### Daily Sales Behavior

![Daily sales](img/plot4_vendas%20diarias.png)

Daily sales fluctuate significantly across the year, with visible peaks that may reflect campaigns, events, or seasonal demand.

Towards early 2025 there is a noticeable increase in activity.

---

### Monthly Revenue Trends

![Monthly revenue](img/plot9_faturamento%20mensal.png)

Monthly aggregation helps reveal seasonality patterns.

For example:

- **May 2024** recorded the highest sales volume.
- **April 2024** showed the lowest activity.

Understanding these patterns helps plan marketing campaigns and staffing decisions.

---

## Business Insights

From a business perspective, several insights emerge:

- Core products such as **Latte and Americano with Milk** drive a large share of revenue.
- **Espresso acts as a low-price entry product**, potentially attracting new customers.
- Sales fluctuate throughout the year, indicating opportunities for seasonal promotions.
- Sundays show lower demand, suggesting opportunities for targeted campaigns.

---

## Next Steps

Possible extensions of this project include:

- Adding cost data to estimate **product margins**
- Building a **simple demand forecasting model**
- Exploring customer segmentation
- Automating monthly reporting dashboards

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## Context

This was the first end-to-end data analysis project I developed independently.  
I chose the topic because of my interest in the coffee market and my previous experience working with sales, which helped guide the analysis toward practical business insights rather than purely technical outputs.
