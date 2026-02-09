# Retail Sales Analysis with Python: Exploratory Data Analysis and Business Insights


1. Business Context
Retail companies generate large volumes of transactional data, but without proper analysis, it is difficult to extract actionable insights.
This project explores retail sales data to evaluate sales performance, profitability, and the impact of discount strategies on business outcomes.

3. Project Objective
. Analyze sales and profit performance
. Identify trends and patterns in customer purchasing behavior
. Evaluate the impact of discounts on profitability
. Provide data-driven business recommendations

3. Business Questions
Key business questions:
. How have sales and profits evolved over time?
. Which regions and categories generate the highest revenue and profit?
.  Are there products with high sales but low or negative profitability?
. Is there seasonality in sales performance?
. How do discounts affect sales and profit?
  
4. Dataset:
. Source: Superstore Sales Dataset (public dataset)
. Records: ~10,000 orders
. Time period: 2014–2017
. Main features: sales, profit, discount, category, region, order date


5. Tools & Technologies
Tools used:
. Python
. Pandas
. NumPy
. Matplotlib / Seaborn
. Jupyter Notebook

6. Analysis Overview
The analysis includes:
. Data cleaning and preprocessing
. Exploratory data analysis (EDA)
. Aggregations by time, region, and category
. Correlation analysis between discounts, sales, and profit
. Data visualization to support insights

7. Key insights: #Incluir gráficas
. Sales increased over time, but profit growth did not follow the same trend.
. The West region generated the highest sales, but not the highest profit margin.
. Some high-selling products consistently generated losses due to high discounts.
. Higher discounts increased sales volume but significantly reduced profitability.

8. Business recommendations:
. Review discount strategies, especially for low-margin products.
. Focus on profitable categories rather than purely high-volume sales.
. Implement targeted promotions instead of broad discounts.

9. Project structure:
├── notebooks/
│   └── superstore_eda.ipynb
├── data/
│   ├── raw/
│   └── processed/
├── images/
│   └── charts/
└── presentation/
    └── Executive_Summary.pdf 
