# SEEDB-Based Visualization Recommendation System

This project is a reproduction of the algorithm and evaluation methodology from the paper *“SEEDB: Efficient Data-Driven Visualization Recommendations to Support Visual Analytics.”* It focuses on optimizing aggregate queries using Shared-based and Pruning-based techniques to recommend insightful visualizations from the UCI Census dataset.

## Project Overview
- **Objective:** Identify top-K aggregate visualizations that highlight significant differences between married and unmarried individuals.
- **Dataset:** UCI Census dataset (32,561 records, 15 features).
- **Tech Stack:** Python, SQLite, Pandas, Matplotlib, NumPy

## Key Features
- **Data Preprocessing:** Handled missing values using mode imputation; mapped marital status to 'Married' and 'Unmarried'.
- **Shared-based Optimization:** SQL query rewriting to compute aggregate functions efficiently.
- **Pruning-based Optimization:** Used K-L Divergence to rank visualizations based on their information utility.
- **Top-K Visualizations:** Generated plots highlighting key insights across demographic and financial attributes.

## Sample Insights
- Married individuals generally showed higher capital losses and gains across educational levels.
- Unmarried individuals had zero capital loss in lower education levels.

##  Future Work
- Scale the system for larger datasets
- Explore alternate utility metrics beyond K-L Divergence
- Perform sensitivity analysis for robustness

## 🔗 Code
[GitHub Repository]((https://github.com/Noshitha/SEEDDB_Visual_Recommendation_System.git))

