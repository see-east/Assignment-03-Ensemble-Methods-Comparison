# Assignment-03-Ensemble-Methods-Comparison
ISYS 312U: Predictive Analytics
# Feature Importance Analysis in the Automotive Industry

## Industry/Domain
This project focuses on Advertising for the Automotive Industry, specifically analyzing factors that influence vehicle sales, pricing, and advertising effectiveness. The goal is to identify which features have the greatest impact on predictive models for sales and customer engagement.

## Dataset Description and Source
Data from the Global EV Sales: 2010-2024 data set on Kaggle
Link to data set on Kaggle: https://www.kaggle.com/datasets/patricklford/global-ev-sales-2010-2024
The dataset includes vehicle-level information such as:  
- `value` – vehicle price  
- `year` – model year  
- `region` – geographic market (e.g., Europe, China, India, Rest of the World)  
- `category` – historical vs projected sales data  
- `mode` – vehicle type (Cars, Vans, Buses)  

The data was sourced from 'IEA Global EV Data 2024.csv' downloaded by the author which captured both historical sales performance and projections across multiple global regions.

## Summary of Findings
Three predictive models were used —**Single Decision Tree**, **Random Forest**, and **Gradient Boosting**—to analyze feature importance and model performance. Key takeaways include:  

- Ensemble methods (Random Forest and Gradient Boosting) significantly outperform a single decision tree, particularly in **precision** (79% → 97–98%).  
- **Top features** driving predictions were `value` and `year`, with regional variations also important. Gradient Boosting additionally highlighted `category_Historical` as a critical factor.  
- Differences in feature importance between methods suggest that combining insights from multiple models provides a more robust understanding of what drives sales and customer behavior.  
- Business implications include optimizing advertising spend, prioritizing high-value leads, and tailoring strategies by region and vehicle category.  

This analysis demonstrates the value of ensemble methods in the automotive domain, enabling more precise targeting and better-informed business decisions.

