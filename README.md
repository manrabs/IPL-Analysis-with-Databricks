# IPL Data Analysis with Databricks

## Project Overview

This project analyzes Indian Premier League (IPL) cricket data using Databricks, PySpark, and various data visualization libraries. It showcases the journey from understanding cricket basics to performing advanced data analysis and visualization techniques.

## Background

As someone new to cricket, I embarked on a learning journey to understand the sport and the Indian Premier League before diving into the data analysis. This project reflects not only the technical aspects of data processing but also the domain knowledge acquired along the way.

## Data Source

The dataset used in this project is sourced from Kaggle and stored in AWS S3. It contains comprehensive information about IPL matches, including player statistics, team performances, and match outcomes.

## Technology Stack

- Databricks: Cloud-based big data processing platform
- PySpark: Python API for Apache Spark
- Spark SQL: SQL interface for Spark
- Matplotlib & Seaborn: Data visualization libraries

## Key Features

1. **Data Loading and Preprocessing**
   - Importing data from AWS S3 to Databricks
   - Cleaning and structuring the dataset for analysis

2. **Advanced Data Manipulation**
   - Utilizing PySpark for complex data transformations
   - Adding new columns using aggregations and window functions
   - Extracting insights such as toss impact and win margins

3. **SQL Analysis**
   - Creating views for specialized queries
   - Analyzing top-scoring players per season
   - Evaluating toss impact on individual matches

4. **Data Visualization**
   - Generating visualizations for key performance metrics
   - Depicting average runs in matches won for winning teams
   - Showcasing top economical bowlers
  
## Key Insights

- Toss Impact Analysis: Evaluation of how winning the toss affects match outcomes
- Player Performance Metrics: Identification of top performers across seasons
- Team Strategy Insights: Analysis of successful batting and bowling strategies

## Getting Started

1. Clone this repository
2. Set up a Databricks environment and configure AWS S3 access
3. Run the notebook IPL Analysis.ipynb

## Future Work

- Implement machine learning models for match outcome prediction
- Expand the analysis to include more recent IPL seasons
- Develop an interactive dashboard for real-time data exploration

## Contributions

Contributions, issues, and feature requests are welcome.

## Acknowledgements

- Kaggle for providing the initial dataset
- The cricket community for resources on understanding the sport
- Databricks and Apache Spark communities for their excellent documentation
