🏠 Airbnb Price Analysis

A data analysis project exploring Airbnb listing prices, room types, and neighbourhood trends using Python, Pandas, Matplotlib, and Seaborn.

## Project Overview

Airbnb has transformed the way people travel by offering a wide range of accommodation options. In this project, I analyzed Airbnb listing data to understand pricing patterns, room type preferences, and neighbourhood trends.

The goal was to clean the data, perform exploratory data analysis (EDA), and uncover insights that could help hosts and travelers better understand the Airbnb marketplace.


## Dataset Information

The dataset contains Airbnb listings with information such as:

- Price
- Room Type
- Neighbourhood Group
- Reviews
- Availability
- Service Fee
- Host Information

The dataset includes more than 100,000 listings.

---

## Objectives

The analysis was conducted to answer the following questions:

- How are Airbnb listings distributed across New York boroughs?
- Which room types are most common?
- How do prices vary across room types?
- Are there any relationships between pricing and other features?
- Are there any missing values, outliers, or data quality issues?

---

## Data Cleaning

The following preprocessing steps were performed:

- Standardized column names
- Handled missing values
- Removed duplicate records
- Treated outliers using the IQR method
- Corrected inconsistent categorical values
- Checked for invalid price values

---

## Exploratory Data Analysis

The analysis included:

- Price distribution analysis
- Room type analysis
- Neighbourhood distribution analysis
- Correlation analysis
- Price comparison across room types
- Data quality validation

---

## Key Findings

### Market Distribution

- Manhattan and Brooklyn dominate the Airbnb market.
- Queens has a moderate number of listings.
- Bronx and Staten Island contribute only a small share of listings.

### Room Type Preferences

- Entire homes/apartments account for approximately 52% of all listings.
- Private rooms account for approximately 45% of listings.
- Shared rooms and hotel rooms make up only a small percentage of the market.

### Pricing Insights

- The average Airbnb listing price is approximately $624.
- Hotel rooms have a slightly higher average price of approximately $666.
- Most listings fall within a moderate price range rather than extreme pricing levels.

### Correlation Analysis

- Price and service fee show a very strong positive correlation.
- Number of reviews and reviews per month show a moderate positive relationship.
- Most other variables exhibit weak correlations, suggesting that pricing is influenced by multiple factors.

### Data Quality

- No listings with zero or negative prices were found.
- The dataset was suitable for analysis after cleaning and preprocessing.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Outlier Detection
- Data Visualization
- Statistical Analysis
- Business Insight Generation

---

## Conclusion

This project demonstrates the complete data analysis workflow, from data cleaning to insight generation. The analysis revealed that Airbnb listings are heavily concentrated in Manhattan and Brooklyn, with entire homes and private rooms dominating the market. While room type influences pricing, location and other listing characteristics appear to play an important role in determining listing prices.

The project helped strengthen my skills in Python, data preprocessing, visualization, and analytical thinking.