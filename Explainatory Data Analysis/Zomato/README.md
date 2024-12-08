# Zomato Exploratory Data Analysis (EDA)

## Table of Contents
- [Zomato Exploratory Data Analysis (EDA)](#zomato-exploratory-data-analysis-eda)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Dataset Description](#dataset-description)
  - [Objectives](#objectives)
  - [Methodology](#methodology)
  - [Installation](#installation)

## Project Overview
This project conducts an Exploratory Data Analysis (EDA) on the Zomato dataset, which contains information about restaurants, their ratings, cuisines, locations, and other relevant features. The primary goal of this analysis is to extract meaningful insights that can assist stakeholders in making informed decisions in the food and restaurant industry.

## Dataset Description
The dataset used in this analysis is sourced from Zomato and includes the following key features:
- **Restaurant ID**: Unique identifier for each restaurant.
- **Restaurant Name**: Name of the restaurant.
- **Cuisines**: Types of cuisine offered by the restaurant.
- **Location**: Geographical location of the restaurant.
- **Average Cost for Two**: Average cost of a meal for two people.
- **Rating**: Customer rating of the restaurant (out of 5).
- **Votes**: Number of votes received by the restaurant.
- **Reviews**: Customer reviews and feedback.

The dataset is available in CSV format and can be found in the `Zomato/` directory of this repository.

## Objectives
The primary objectives of this EDA are:
1. To analyze the distribution of restaurant ratings and average costs.
2. To identify the most popular cuisines and their average ratings.
3. To explore the relationship between location and restaurant ratings.
4. To visualize trends in customer preferences and behaviors.
5. To provide actionable insights for restaurant owners and marketers.

## Methodology
The analysis follows these steps, as detailed in the `data_analysis.ipynb` notebook:
1. **Data Cleaning**: 
   - Handling missing values and duplicates.
   - Converting data types for analysis.
   - Normalizing text data (e.g., cuisine names).

2. **Descriptive Statistics**: 
   - Generating summary statistics to understand the dataset.
   - Analyzing the distribution of key features.

3. **Data Visualization**: 
   - Creating visual representations of the data using libraries such as Matplotlib and Seaborn.
   - Utilizing various plots (histograms, bar charts, box plots) to illustrate findings.

4. **Correlation Analysis**: 
   - Examining relationships between different features using correlation matrices and scatter plots.

5. **Insights Generation**: 
   - Drawing conclusions based on the analysis and visualizations.
   - Providing recommendations based on findings.

## Installation
To run this project, you need to have Python installed along with the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- jupyter

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```