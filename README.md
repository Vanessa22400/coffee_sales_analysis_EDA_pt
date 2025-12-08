# Coffee Sales Analysis — Exploratory Data Analysis (EDA)

This project analyzes sales data from a coffee shop, with the goal of understanding customer behavior, identifying patterns, and extracting insights that support data-driven decisions in marketing, pricing, and product strategy.

It is one of my first independent Data Science projects, developed to practice exploratory data analysis, visualization, and analytical storytelling using Python.

---

## Objectives

The analysis focuses on answering questions such as:

- Which coffee products generate the highest revenue and sales volume?
- How do sales vary over time (daily, weekly, monthly)?
- Are there identifiable seasonal or recurring patterns?
- How does the average price differ by product?
- Which days of the week show stronger or weaker performance?
- What strategic opportunities can be derived from these trends?

---

## Dataset

The dataset contains coffee shop sales from March 2024 to March 2025.  
Main columns:

- `date` – date of sale  
- `datetime` – time of sale  
- `cash_type` – method of payment  
- `money` – value of the transaction  
- `coffee_name` – type of coffee sold  

This structure supports both product-level and time-based analysis.

---

## Data Preparation

Main preprocessing steps:

1. Conversion of date and datetime columns.  
2. Checking for missing values.  
3. Creation of additional fields:  
   - day of the week  
   - month  

---

## Analyses Performed

### 1. Product Analysis
- Sales volume by product  
- Revenue by product  
- Average price per product  
- Comparison between volume and average ticket  

These steps help identify:
- best-selling items  
- products that drive revenue  
- higher-ticket drinks that may deserve greater visibility  

---

### 2. Time-Based Analysis
Analysis by:
- day  
- weekday  
- month  

Key findings include:
- growth toward the end of the period  
- a significant sales peak in October 2024  
- higher activity on weekdays  
- lower demand on Sundays  

---

## Business Insights

Some potential strategic actions based on the data:

- Plan marketing campaigns around months with historically higher demand.  
- Promote Espresso as an accessible option to attract new customers.  
- Explore discounts or combos on high-performance weekdays such as Tuesday.  
- Create Sunday campaigns to increase traffic on the lowest-performing day.  
- Automate monthly sales dashboards for faster strategic adjustments.

---

## Future Improvements

- Add cost data to calculate product margins.  
- Use payment data to explore basic customer segmentation.  
- Build a simple forecasting model for monthly sales.  
- Automate monthly reports with Python.

---

## Tools Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  
