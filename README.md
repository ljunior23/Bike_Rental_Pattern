# Bike Rental Pattern Analysis
## Summary

This project analyzes bike rental data to uncover patterns and insights about user behavior, time trends, and the impact of holidays, weather, and seasons. Using Python libraries such as pandas, seaborn, and matplotlib, the notebook performs data cleaning, feature engineering, and visualization. Key steps include:

- Loading and exploring daily and hourly rental datasets
- Handling missing values and outliers
- Creating new time-based and categorical features
- Visualizing rental trends by hour, day, season, weather, and user type (casual vs registered)
- Comparing rentals on holidays vs non-holidays and weekdays vs weekends
- Clustering time periods to analyze user activity

The visualizations help identify peak rental times, the influence of external factors, and differences between casual and registered users. This analysis supports better understanding of urban mobility and can inform operational decisions for bike rental services.

# Bike Rental Pattern Analysis

## Project Overview

This project explores and analyzes bike rental data to uncover usage patterns, trends, and factors affecting rentals. The analysis is performed in a Jupyter notebook using Python libraries such as pandas, seaborn, and matplotlib.

## Key Features

- **Data Loading & Cleaning:** Import daily and hourly rental datasets, handle missing values and outliers.
- **Feature Engineering:** Create new time-based and categorical features for deeper analysis.
- **Exploratory Analysis:** Visualize rental trends by hour, day, season, weather, and user type (casual vs registered).
- **Comparative Insights:** Compare rentals on holidays vs non-holidays, weekdays vs weekends.
- **Clustering & Visualization:** Group time periods and analyze user activity with advanced plots.

## Insights
- Identifies peak rental times and seasonal trends.
- Shows the impact of weather, holidays, and user type on rental counts.
- Provides actionable information for improving bike rental operations.

## Requirements

- Python 3.x
- pandas
- seaborn
- matplotlib
- numpy

## Usage

1. Open the notebook `bike_rental.ipynb` in Jupyter or VS Code.
2. Ensure the datasets (`day.csv`, `hour.csv`) are available in the specified directory.
3. Run the cells sequentially to reproduce the analysis and visualizations.
