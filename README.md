# Amazon Product Analysis & Recommendation System

## Project Overview
This project analyzes over 1,400 Amazon products to uncover key factors influencing customer satisfaction, product popularity, and pricing strategies.

The analysis also includes a simple recommendation system to identify high-value products based on rating, engagement, and discount metrics.

---

## Objectives
- Identify top-performing product categories  
- Analyze the relationship between discounts and product ratings  
- Determine factors influencing product popularity  
- Build a simple product recommendation system  

---

## Tools Used
- Python (pandas, numpy)  
- Matplotlib  
- Jupyter Notebook  

---

## Key Insights

### 1. Category Performance
- Tablets and networking devices recorded the highest average ratings (~4.5+)  
- High-engagement categories include headphones, USB cables, and smartphones  

Insight: Specialized categories show higher satisfaction, while mass-market electronics dominate engagement.

---

### 2. Discount vs Rating
- Weak negative correlation (-0.156)

Insight: Discounts do not significantly improve product ratings, indicating that product quality is more important than pricing incentives.

---

### 3. Popularity Drivers
- Rating vs popularity: weak positive (0.10)  
- Price vs popularity: negligible (-0.036)  
- Discount vs popularity: negligible (0.01)  

Insight: Popularity is influenced more by demand and product visibility than pricing or rating alone.

---

### 4. Top Products
- High review counts dominated by HDMI cables and audio accessories  

Insight: Frequently used and affordable products drive the highest engagement.

---

## Recommendation System
A rule-based system was developed to identify high-value products using:
- Rating ≥ 4.0  
- Rating Count ≥ 1000  
- Discount ≥ 20%  

This approach highlights products that balance quality, popularity, and affordability.

---

## Conclusion
- Product quality is the main driver of customer satisfaction  
- Discounts alone do not guarantee better ratings or engagement  
- Product type and demand strongly influence popularity  
- Data-driven filtering can effectively identify high-value products  
