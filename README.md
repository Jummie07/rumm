# **Adidas US Sales Analysis**

## **Table of Contents**

- [Project Overview](project_overview)
- [Data Source](data_source)
- [Tools Used](tools_used)
- [Data Cleaninig](data_cleaning)
- [Exploratory Data Analysis (EDA)](exploratory_data_analysis_(EDA))
- [Data Analysis](data_analysis)
- [Data Insights](data_insights)
- [DAX Used in Power Query](dax_used_in_power_query)
- [Results of DAX](results_of_dax)
- [Recommendations](recommendations)
- [Conclusion](conclusion)
- [Future enhancements](future_enhancements)
---

### **Project Overview**
---
This project aims to provide a comprehensive data analysis of Adidas sales performance in the US through Power BI. It provides critical insights into total sales, revenue, profit, product performance, and retailer contributions. The dashboard created is an essential tool for identifying trends, optimizing sales strategies, and driving informed business decisions.


![image](https://github.com/user-attachments/assets/15f9b029-0e7e-4cd1-939d-ce2e48b2fdbf)

[Product perfomance in each State]

![Visual 1](https://github.com/user-attachments/assets/ec2b79bd-4420-4e47-9476-562f69fd6b24)]

[Top performing Product]

![Visual 3](https://github.com/user-attachments/assets/b18144ac-8e31-4b48-8c63-c9461702bdbd)


[![Visual 4](https://github.com/user-attachments/assets/a6fa7d53-d1df-4e81-8006-02aafe52c0ac)]

[Retailer with the most Sales]

---

### **Data Source**

The dataset was obtained from [Kaggle]. It includes retailers id, invoice date, region, state, city, product, price per unit, unit sold, total sales, profit margins, operating profit, and sales method.

---

### **Tools Used**

  - Power Query – Data cleaning 
  - DAX (Data Analysis Expressions) – For calculations
  - Power BI – Data visualization & Dashboard creation

---

### **Data Cleaning**

  - Removed First 6 rows as they contained null.
  - Removed Colums with null.
  - Removed duplicates and null values.
  - Standardized product categories and sales methods.
  - Formatted date and currency fields.
  - Created new calculated column Total Revenue, Month Name.

---

### **Exploratory Data Analysis (EDA)**
  - Identified trends in total sales, revenue, and profit over time.
  - Examined top-selling products and best-performing retailers.
  - Analyzed sales distribution across different states.
  - Analyzed month with the higest profit.

---

### **Data Analysis**
1. Total Sales & Profit Analysis:
    - Total revenue: $49bn
    - Total profit: $102T (potentially a data formatting issue)
    - Units sold: 2M
    - Total Profit by Month shows a steady decline from $12.8T to $5.3T, which indicate potential operational inefficiencies or seasonal trends.
      
2.  Product Performance Analysis:
    - Top-Selling Product Categories (by revenue):

      - Women's Apparel: $11.1bn
      - Men’s Footwear: $8.1bn
      - Men’s Streetwear: $7.3bn
      - Women’s Footwear: $6.5bn
      
    - Highest Units Sold:

      - Men’s Street Footwear: 0.59M units
      - Men’s Athletic Apparel: 0.46M units
    
3.  Regional Analysis
   
    - Total Sales by State and Product suggests major sales concentrations in:

      - California, Texas, and New York – High revenue-generating states
      - Lower sales in Midwest & rural areas, indicating potential for market expansion.
      
4.  Retailer Contribution Analysis
     - Top Retailers by Revenue:
  
      - West Gear: $0.24bn
      - Foot Inc.: $0.22bn
      - Amazon: $0.07bn
  ---
      
### **Data Insights**
The basic key insights for this analysis is:
  - Thers is a sales decline over time, revenue & profit show a downward trend, indicating a need for a pricing or marketing strategy shift.
  - Women’s Apparel dominates revenue, but Men’s Street Footwear sells more units, this suggests potential pricing optimization for footwear.
  - West Gear & Foot Inc. dominate sales, but Amazon has lower revenue share, indicating potential for better e-commerce strategies.
  - Retail sales depend heavily on physical stores. The Online sales contribute less, indicating an opportunity to expanding digital/online channels.
  - Top performing States drive most revenue, while other states remain untapped markets for growth opportunities.

---

### *DAX Used in Power Query*
Created calculated columns and measures such as;
```Power_Query
    Total Revenue: SUM(Sales[Revenue])
```
---

### *Results of DAX*
Aggregated revenue and profit by product category.

---

### **Recommendations**
1.  Boost Online Sales:
    - Invest in digital(online) marketing & e-commerce strategies to increase online sales.
    - Expand presence on Amazon & online retail platforms.
2.  Focus on High-Revenue Products:
    - Women’s Apparel & Men’s Footwear should receive more marketing investment.
    - Consider pricing strategy adjustments for high-selling but lower-revenue products.
3.  Expand into Underserved States:
    - Increase presence in Midwest & rural regions where sales are low.
    - Consider localized promotions & store expansions.
4.  Investigate Profit Decline:
    - Investigate potential errors in Total Profit ($102T) and adjust calculations.
    - Review operational costs & profit margins to identify potential inefficiencies.
    - Adjust pricing models to maintain profitability.

  ---

### **Conclusion**

This analysis delivers a thorough overview of Adidas sales in the US, empowering stakeholders to make informed, data-driven decisions. We are poised to enhance it further by incorporating advanced predictive modeling and customer segmentation for even deeper insights.

---

### **Future enhancements**

  - Predictive modeling for sales forecasting.
  - Customer segmentation for targeted marketing.
---


