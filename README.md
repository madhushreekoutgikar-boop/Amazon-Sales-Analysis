       
# Project Overview

  This project analyzes Amazon product sales data to uncover key business insights related to revenue, product performance, customer engagement, and seasonal trends.
  The dashboard is built using Power BI and supported by SQL-based analysis.   

## PROBLEM STATEMENT

### KPI's REQUIREMENT

➤ YTD Sales: Monitor year-to-date sales to gauge the overall revenue performance over time.

➤ QTD Sales: Track quarterly sales figures to identify sales trends and fluctuations.

➤ YTD Products Sold: Analyse the total number of products sold throughout the year to understand product movement.

➤ YTD Reviews: Keep tabs on year-to-date product reviews to assess customer feedback and satisfaction.
  

### Objectives

- Track overall sales performance (YTD & QTD)  
- Identify top-performing products and categories
- Analyze sales trends over time (monthly & weekly)
- Evaluate customer engagement using reviews
- Provide actionable insights for business growth

 
 ### Data Modeling

<img width="966" height="450" alt="image" src="https://github.com/user-attachments/assets/bed1f73b-0781-44c4-95a2-33e871e68b34" />


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
   
3. Improve underperforming segments (Mobile & Accessories)
   
5. Leverage customer reviews for product improvements
   
7. Increase inventory during peak months



   
- Clean and professional UI design
