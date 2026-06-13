# Analysis-Urban Movility
# Urban Mobility & Economic Productivity Analysis in Latin America

# Overview

This project explores the relationship between urban mobility and economic productivity across major Latin American cities. Using real-world data from the TomTom Traffic Index and OECD Cities, I cleaned, transformed, merged, and analyzed traffic and economic indicators to investigate whether traffic congestion is associated with economic performance.

The goal was to identify patterns that could help policymakers, investors, and urban planners prioritize transportation infrastructure investments.

# Business Question

How does urban mobility impact economic productivity in Latin American cities?

# Specifically:

Are cities with higher traffic congestion less productive economically?
Is there a measurable relationship between congestion metrics and GDP per capita?
Which cities could benefit most from transportation infrastructure improvements?
Datasets
Traffic Data

# Source: TomTom Traffic Index
# Key metrics:

Traffic Index
Traffic Delay (minutes)
Traffic Jam Length (km)
Number of Traffic Jams
Live Travel Time per 10 km
Historical Travel Time per 10 km
Economic Data

# Source: OECD Cities
# Key metrics:
GDP per Capita
Unemployment Rate
PM2.5 Air Pollution
Population
Project Workflow
1. Data Exploration
Loaded and inspected both datasets
Reviewed data structures and column types
Identified formatting inconsistencies and missing values
2. Data Cleaning
Standardized column names using snake_case
Converted date fields to datetime
Cleaned numeric fields with mixed international formats
Converted percentages and population values to numerical formats
3. Feature Engineering
Extracted year information from traffic timestamps
Filtered data to focus on 2024
Created city-level aggregated traffic indicators
4. Data Aggregation
Calculated annual averages by:
City
Country
Year

# Key aggregated metrics:

Average congestion delay
Average traffic index
Average travel time
Average jam count and length
5. Data Integration

Merged mobility and economic datasets using:

city
year

This created a unified analytical dataset for further exploration.

6. Exploratory Data Analysis (EDA)

Built visualizations including:

Boxplots
Histograms
Comparative bar charts

Investigated relationships between:

GDP per capita
Traffic congestion
Travel times
Urban mobility indicators
7. Export & Documentation
Produced a clean analytical dataset
Exported final results to CSV
Documented findings and conclusions


# Key Findings
1. Mexico City showed the highest average traffic congestion

Among the analyzed cities, Mexico City exhibited the largest average traffic delay, highlighting the scale of mobility challenges in major metropolitan areas.

2. No strong linear relationship was observed

The analysis did not reveal a clear linear relationship between GDP per capita and traffic congestion.

3. Economic performance depends on multiple factors

Examples from the dataset suggest that:

Some cities maintain strong economic performance despite heavy congestion.
Others combine lower congestion with high productivity.

This indicates that urban mobility is only one of several factors influencing economic outcomes.

4. Infrastructure decisions require broader analysis

Transportation investments should be evaluated alongside:

Urban planning
Labor market conditions
Environmental factors
Population density
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Skills Demonstrated
Data Cleaning
Data Transformation
Exploratory Data Analysis (EDA)
Data Aggregation
Data Integration (Joins/Merges)
Feature Engineering
Data Visualization
Business Insight Generation
Analytical Reporting
Repository Structure
├── Analysis-Urban Mobility.ipynb
├── ladb_mobility_economy_2024_clean.csv
└── README.md
Executive Summary

This project analyzed the connection between urban traffic conditions and economic productivity across Latin American cities using real-world mobility and economic datasets. After cleaning, transforming, and integrating the data, city-level indicators were examined through exploratory analysis and visualization.

The results suggest that traffic congestion alone does not explain economic productivity. While some cities experience both high GDP per capita and severe congestion, others achieve strong economic performance with lower traffic levels. These findings reinforce the importance of considering multiple urban and economic factors when evaluating infrastructure investment opportunities.

# About This Project

This project was completed as part of a data analytics portfolio to demonstrate practical skills in data preparation, exploratory analysis, visualization, and business-focused insight generation using Python and real-world datasets.
