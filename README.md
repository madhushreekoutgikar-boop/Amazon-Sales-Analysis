# Amazon Sales Analysis          


  
## Project Overview

  This project analyzes Amazon product sales data to uncover key business insights related to revenue, product performance, customer engagement, and seasonal trends.
  The dashboard is built using Power BI and supported by SQL-based analysis.   

  

### Objectives

- Track overall sales performance (YTD & QTD)  
- Identify top-performing products and categories
- Analyze sales trends over time (monthly & weekly)
- Evaluate customer engagement using reviews
- Provide actionable insights for business growth

  

### Dashboard Preview

<img width="1285" height="716" alt="image" src="https://github.com/user-attachments/assets/9ba4c79e-2bf6-4d60-bc63-d14859ed0494" />


### Key KPIs

-  YTD Sales: $2.18M
-  QTD Sales: $811.09K
-  Products Sold (YTD): 27.75K
-  Total Reviews: 19.42M

### Key Insights

- Sales show a strong upward trend in the last quarter
- Peak performance observed in November & December
- Men Shoes category contributes the highest sales (~43%)
- Some categories like Mobile & Accessories underperform
- High review count indicates strong customer engagement

### Dashboard Features

- Interactive filters (Product, Quarter)
  
- Sales analysis by:
  * Month 
  * Week
     
- Product Category
  
- Top 5 products by:
  * Sales 
  * Reviews


### SQL Analysis (Sample Queries)

🔹 Total Sales
SELECT SUM(sales) FROM amazon_data;

🔹 Top Products
SELECT product_name, SUM(sales) AS revenue
FROM amazon_data
GROUP BY product_name
ORDER BY revenue DESC
LIMIT 5;

### Business Recommendations

1. Focus marketing on high-performing categories
2. Improve underperforming segments (Mobile & Accessories)
3. Leverage customer reviews for product improvements
4. Increase inventory during peak months
   
- Clean and professional UI design
