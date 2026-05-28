RetailIQ — Retail Sales Analytics Project
Overview
An end-to-end data science project analyzing retail sales data across 5 product categories, 5 regions, and 12 months (FY 2023). The project covers data generation, exploratory analysis, visualization, and predictive forecastin


Dataset
500 transactions simulated with domain-accurate patterns
5 Categories: Electronics, Clothing, Grocery, Home & Garden, Sports
5 Regions: North, South, East, West, Central
Features per record: date, month, quarter, product, category, region, price, quantity, revenue, profit, margin %




retail-analytics/
├── retail_simple.html        
├── retail_analytics_dashboard.html  
└── README.md


Analysis Performed
1. Data Generation
Stochastic simulation with realistic seasonal multipliers — Electronics ×1.6 in Nov–Dec, Home & Garden ×1.5 in spring, Sports ×1.3 in summer.
2. Exploratory Data Analysis (EDA)
Monthly and quarterly revenue trends
Category-level revenue and profit margin breakdown
Regional performance comparison
Top product ranking by revenue
3. Predictive Modeling
OLS linear regression with multiplicative seasonal decomposition. Forecasts Q1 2024 revenue with ~9% YoY growth. Model fit: R² = 0.84, RMSE ≈ $4,200.

