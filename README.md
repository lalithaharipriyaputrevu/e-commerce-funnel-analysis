                                            **E-Commerce Purchase Funnel Analysis**

Analysis of 2.7M+ user behavior events from a cosmetics e-commerce store to identify purchase funnel drop-off points, conversion patterns, and revenue opportunities.

  [View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/lalitha.haripriya.putrevu/viz/Funnelanalysis_17777617573710/FunnelAnalysisDashboard)

##  Business Problem

Out of every 100 people who view a product, only 10 actually buy it.  
**Where are the other 90 dropping off — and why?**

This project maps the complete purchase funnel from product view to cart to purchase and identifies which categories, price points, and time patterns drive the most conversions and revenue.

## Key Findings

 1.  **Only 10% of product views converted to purchases** — 90% of potential customers dropped off before buying  
 2. **Apparel.glove had the highest conversion rate at 44.22%** — nearly 2x higher than stationery.cartridge (24.27%)   
 3. **Peak purchase hour is 12pm (noon)** with 17,500+ transactions — ideal time for promotions and campaigns   
 4.  **Furniture categories had the highest cart abandonment** at 60%+ — representing the biggest revenue recovery opportunity
 5. **Stationery drove the highest total revenue** despite not having the top conversion rate — higher average order value 
 6.  **Low-priced products (under $20) had the highest conversion rates** — price is a significant purchase barrier above $50 

## Funnel Breakdown
  View | 2,037,608   
  Cart | 1,148,323 | 43.6% dropped   
  Remove from Cart | 815,024    
  Purchase | 263,797 | 87.1% dropped from view 

##  Tools Used
| Python (Pandas, NumPy) | Data cleaning & exploratory analysis   
| SQL (SQLite) | Funnel queries & aggregations   
| Tableau Public | Interactive dashboard & visualizations   
| GitHub | Version control & portfolio   

##  Analysis Breakdown

### 1. Funnel Analysis
- Mapped complete user journey from view → cart → purchase
- Identified 90% overall drop-off rate
- Calculated stage-by-stage conversion rates

### 2. Conversion Rate by Category
- Apparel.glove: **44.22%** (highest)
- Stationery.cartridge: **24.27%**
- Furniture.bathroom.bath: **11.98%**
- Appliances: **9.38% – 8.97%**

### 3. Cart Abandonment Analysis
- Furniture categories had **60%+ abandonment rate**
- Appliances had the lowest abandonment rate

### 4. Revenue Analysis
- Stationery drove the **highest total revenue ($600+)**
- Furniture categories followed despite high abandonment
- Low-revenue categories need pricing or marketing strategy review

### 5. Price vs Conversion Rate
- Products under **$20 had the highest conversion rates (0.4+)**
- Products above **$100 had near-zero conversion rates**
- Clear negative correlation between price and conversion

### 6. Time-Based Analysis
- Peak purchases at **12pm UTC** (17,500+ transactions)
- Second peak around **8–9pm UTC**
- Lowest activity between **2am – 6am UTC**

##  Dataset

- **Source:** Kaggle - eCommerce Events History in Cosmetics Shop
- **Size:** 2.7M+ rows, 9 columns
- **Period:** January - February 2020
- **Events tracked:** view, cart, remove_from_cart, purchase
