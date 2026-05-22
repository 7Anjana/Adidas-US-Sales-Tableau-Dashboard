# Adidas US Sales Dashboard | Tableau Project

## Overview

The Adidas US Sales Dashboard is an interactive business intelligence project developed using Tableau Public to analyze Adidas retail product performance across the United States. The dashboard provides data-driven insights into product categories, customer preferences, pricing patterns, product availability, and customer engagement metrics.

This project transforms raw retail data into meaningful visual analytics that support strategic decision-making in inventory management, pricing optimization, product marketing, and customer targeting.

---

## Business Problem

Retail businesses generate large amounts of product and customer data, but extracting meaningful insights from that data can be challenging. This project focuses on analyzing Adidas US retail product data to identify:

- High-performing product categories
- Customer engagement trends
- Pricing and rating patterns
- Inventory availability
- Audience segmentation
- Popular product colors and products

The dashboard helps stakeholders make informed business decisions using interactive visualizations and KPI metrics.

---

## Objectives

- Analyze overall Adidas product portfolio performance
- Identify the most dominant product categories
- Evaluate customer engagement using reviews and ratings
- Understand pricing distribution and market positioning
- Study target audience segmentation
- Discover top-selling and high-performing products
- Provide actionable business recommendations

---

## Dataset Information

### Dataset Name
Adidas US Sales Dataset

### Dataset Size
- Total Products: 845
- Total Columns: 21

### Dataset Attributes
- Product Name
- Category
- Selling Price
- Product Rating
- Review Count
- Product Color
- Availability Status
- Target Audience

---

## Tools & Technologies

- Tableau Public
- Microsoft Excel
- CSV Dataset
- Data Visualization
- Business Intelligence & Analytics

---

## Dashboard Components

### KPI Cards
The dashboard includes key performance indicators to provide a quick overview of business performance.

- Total Products
- Total Reviews
- Average Price
- Average Rating

---

### Visualizations Used

#### Category-wise Distribution
Displays the distribution of products across different categories such as Shoes, Clothing, and Accessories.

#### Target Audience Distribution
Shows audience segmentation including Men, Women, Kids, and Unisex products.

#### Availability Analysis
Visualizes product stock availability and out-of-stock products.

#### Top Selling Products
Highlights the highest-performing Adidas products using bubble chart visualization.

#### Color Distribution
Analyzes customer preference for different product colors.

#### Price Distribution Histogram
Displays product pricing patterns and identifies the most common price ranges.

---

## Calculated Field

### Target Audience Classification

```Tableau
IF CONTAINS([Products], "Women") THEN "Women"
ELSEIF CONTAINS([Products], "Men") THEN "Men"
ELSEIF CONTAINS([Products], "Kids") THEN "Kids"
ELSE "Unisex"
END
```

---

## Key Insights

- Shoes represent the highest-performing product category.
- Women-focused products dominate the target audience segment.
- White and Black products show the strongest customer preference.
- Most Adidas products fall within the mid-range pricing category.
- The average product rating exceeds 4.6, indicating strong customer satisfaction.
- High review counts reveal products with strong market engagement and popularity.

---

## Business Recommendations

- Expand inventory for high-performing product categories.
- Increase production of popular color variants such as White and Black.
- Promote highly rated products with lower market visibility.
- Focus marketing strategies on mid-price range products.
- Use customer engagement metrics to improve targeted advertising campaigns.

---

## Future Enhancements

- Real-time sales data integration
- Regional sales analysis dashboard
- Predictive analytics for inventory forecasting
- Customer segmentation and behavior analysis
- Integration with SQL databases and cloud platforms

---

## Project Outcome

This project demonstrates the use of Tableau for transforming raw retail data into meaningful business insights through interactive dashboards and visual storytelling. The dashboard supports better business decisions by providing a clear understanding of product performance, customer behavior, and market trends.

---

## References

- Adidas US Sales Dataset – Kaggle
- Tableau Public Documentation

---

## Author

### Anjana Sabu
BTech Computer Science and Engineering Graduate
Focused on Data Analytics, Business Intelligence, and Visualization Projects

---
