# Coffee Sales Analysis: Revenue Strategy and Demand Patterns
*Exploratory analysis of coffee shop sales data to understand product performance, demand patterns and practical opportunities to improve revenue.*

**Dataset:** 3,636 coffee shop transactions (March 2024 – March 2025)  
**Techniques:** Exploratory Data Analysis (EDA), temporal analysis, revenue analysis  
**Key Result:** Identification of core revenue drivers, seasonal demand patterns and opportunities for targeted promotions

---

## Business Context

Coffee shops operate in a highly dynamic environment where demand fluctuates daily and seasonally. Small improvements in product positioning, promotions and operational planning can have a meaningful impact on revenue.

Understanding **which products drive revenue**, **when demand peaks**, and **where operational opportunities exist** can help businesses make more informed decisions regarding pricing, marketing actions and staffing.

Even though this project uses a public dataset, the analysis is framed as a realistic business scenario where data analysis supports strategic decision-making and revenue optimization.

---

## Dataset

Source:  
https://www.kaggle.com/datasets/ihelon/coffee-sales

Dataset characteristics:

• **3,636 sales transactions**  
• Period: **March 2024 – March 2025**  
• Transaction-level data  

Key variables:

• `date` — date of the transaction  
• `datetime` — timestamp of the sale  
• `cash_type` — payment method  
• `money` — transaction value  
• `coffee_name` — type of product sold  

An operational observation is that **97.5% of transactions are card payments**, suggesting a highly digital customer base.

---

## Problem Statement

How can transactional sales data be analyzed to identify **product performance, revenue drivers and demand patterns**, and how can these insights support better operational and strategic decisions in a coffee shop business?

---

## Objectives

- Identify the products that drive **sales volume and revenue**
- Perform structured **exploratory data analysis**
- Analyze **temporal patterns** in daily, weekly and monthly demand
- Understand differences between **high-volume products and high-revenue products**
- Translate analytical findings into **business insights and recommendations**

---

## Methodology

1. **Data Cleaning and Preprocessing**  
Conversion of date variables, validation of missing values and preparation of time-based variables such as month, weekday and hour.

2. **Exploratory Data Analysis**  
Identification of patterns in product demand, revenue distribution and temporal behavior.

3. **Temporal Analysis**  
Investigation of daily, weekly and monthly patterns to detect seasonal fluctuations and operational opportunities.

4. **Revenue Analysis**  
Comparison between product popularity and revenue generation to understand the role of different products in the overall revenue mix.

5. **Insight Generation**  
Translation of statistical findings into practical business insights and strategic recommendations.

---

## Tools & Technologies

• Python  
• Pandas  
• NumPy  
• Matplotlib  
• Seaborn  
• Google Colab  

---

## Exploratory Data Analysis Highlights

The exploratory analysis revealed several patterns relevant for business decision-making.

### Product Demand

![Sales by Coffee Type](img/plot1_Vendas%20por%20tipo%20de%20café.png)

**Figure:** Sales volume by coffee type.

The most frequently sold products are:

• Americano with Milk (824)  
• Latte (782)  
• Americano (578)  

These products represent the **core demand of the coffee shop**.

---

### Revenue Drivers

![Revenue by Coffee Type](img/plot2_Faturamento%20por%20Tipo%20de%20Café.png)

**Figure:** Total revenue by coffee type.

The top revenue contributors are:

• Latte (27,866)  
• Americano with Milk (25,269)  
• Cappuccino (18,034)

**Key insight:** products with slightly lower sales volume can still contribute strongly to total revenue due to higher prices.

---

### Seasonal Revenue Patterns

![Monthly Revenue](img/plot9_faturamento%20mensal.png)

**Figure:** Monthly revenue trend.

The monthly aggregation reveals fluctuations in demand across the year.

For example:

• **May 2024 shows the strongest sales performance**  
• **April 2024 shows the lowest activity**

Understanding these patterns helps plan promotions, inventory and staffing decisions.

---

## Key Insights

Several relevant insights emerge from the analysis:

• **Core demand products:** Americano with Milk and Latte represent the base of recurring demand.

• **Revenue concentration:** Latte generates the highest total revenue despite similar volume to other products.

• **Price strategy opportunity:** Espresso functions as a lower-price entry product that may attract customers and enable upselling.

• **Seasonal fluctuations:** Demand varies throughout the year, indicating opportunities for seasonal promotions and targeted campaigns.

---

## Business Impact

The findings from this analysis can support several business decisions.

**Product Strategy**  
Understanding which products drive revenue helps optimize menu positioning and promotional focus.

**Operational Planning**  
Demand fluctuations across months can inform staffing and inventory decisions.

**Marketing Actions**  
Seasonal peaks and weaker periods suggest opportunities for targeted promotions.

**Revenue Optimization**  
Combining high-volume and high-margin products can improve overall profitability.

---

## Next Steps

Potential future improvements include:

• Incorporating **cost data** to analyze product margins  
• Developing a **sales forecasting model**  
• Automating reporting with a **data pipeline**  
• Building a **dashboard for performance monitoring**

---

## Repository Structure

```
.
├── data
├── notebooks
├── images
├── requirements.txt
└── README.md
```


---

## Strategic Perspective

This project was developed independently as an end-to-end data analysis exercise. My analytical approach combines technical exploration with business interpretation, influenced by years of living and working in different countries. This cross-cultural experience helps me question assumptions, interpret context and connect data patterns to real-world decision-making.

---

## Conclusion

This project demonstrates how structured exploratory analysis can transform raw transactional data into meaningful business insight.

The analysis identified the main revenue drivers, revealed seasonal demand patterns and highlighted practical opportunities for operational and strategic improvements.

The focus of the project is not only technical analysis, but also **clarity of insight and real decision-making value.**
