# Big Mountain Resort: Data-Driven Pricing Optimization
## Overview
This project focuses on developing a data-driven strategy to optimize the pricing of lift tickets at Big Mountain Resort, a popular ski destination in Montana. By analyzing data from 330 comparable ski resorts across the U.S., we identified key trends and implemented machine learning models to predict optimal pricing strategies and explore cost-saving opportunities. The resort recently increased its operating costs by adding a new chairlift, and this project aims to balance those expenses with revenue growth through optimized pricing.

## Project Objective
The primary goal is to recommend ticket pricing strategies that maximize Big Mountain Resort’s revenue while maintaining competitive rates within the market. Additionally, the project explores potential operational efficiencies that could help the resort manage costs without compromising the guest experience.

## Dataset
The dataset used in this project includes pricing, operational, and customer data from 330 U.S.-based ski resorts. The data was cleaned to remove incomplete and irrelevant entries, with features engineered for analysis, such as ticket prices, the number of lifts, and resort size.

## Key Steps:
1. Data Cleaning and Preparation:
    - Removed incomplete records and irrelevant features.
    - Created new features such as resort popularity and regional market trends.
2. Exploratory Data Analysis (EDA):
    - Utilized Principal Component Analysis (PCA) to explore relationships between key variables and reduce dimensionality.
    - Identified the variance of features, highlighting which factors contribute most to price differences across resorts.
3. Machine Learning Models:
    - Built two machine learning models: Linear Regression and Random Forest.
    - Used cross-validation to minimize Mean Absolute Error (MAE) and fine-tune model accuracy.
4. Pricing Prediction:
    - The models were used to predict the optimal ticket price for Big Mountain Resort.
    - The analysis suggested that the resort could increase its ticket price from $81 to $92.65, while remaining competitive within the market.
5. Revenue and Cost Analysis:
    - The project explored various pricing scenarios, including the impact of incremental ticket price increases and weekend rate adjustments.
    - A $0.54 increase in ticket price was projected to generate an additional $939,815 in seasonal revenue.
6. Operational Efficiency:
    - Investigated the correlation between ticket prices and the number of ski runs open.
    - Found that closing up to five runs could yield cost savings without significantly affecting customer satisfaction.

## Results
  - The project indicates that Big Mountain Resort's current pricing is competitive but has room for a slight increase.
  - Implementing alternative pricing strategies, such as weekend rate adjustments or season pass bundles, could further offset the increased operating costs from the new chairlift.
  - Operational adjustments, such as reducing the number of open runs during off-peak times, could help reduce maintenance costs without impacting the guest experience.
## Conclusion
This data-driven analysis provides valuable insights for Big Mountain Resort's management team, suggesting that a slight ticket price increase and targeted operational efficiencies could significantly enhance profitability. Future work should include continuously monitoring market trends and exploring more granular pricing models based on customer segmentation and seasonal demand.
## Technologies Used
  - Python: Data cleaning, analysis, and modeling
  - Pandas: Data manipulation
  - Scikit-learn: Machine learning model building
  - Matplotlib/Seaborn: Data visualization
  - Principal Component Analysis (PCA): Dimensionality reduction and feature analysis
  - Random Forest & Linear Regression: Predictive modeling
## Repository Structure
  - 'data/': Contains the dataset used for analysis.
  - 'notebooks/': Jupyter notebooks with code for data cleaning, analysis, and model building.
  - 'models/': Saved machine learning models.
  - 'visualizations/': Plots and visualizations of data trends and model outputs.
  - 'README.md': Project overview and details (this file).
## Future Improvements
  - Gather more data on seasonal demand and customer behavior to enhance model accuracy.
  - Explore advanced pricing models based on dynamic pricing algorithms.
  - Incorporate real-time data for continuous model updates and strategy refinements.
## Author
John Maloney, Data Science Practitioner
