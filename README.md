# Air-BnB-Python-Data-Analysis-Project
## Project Objective
- To analyze Airbnb listing data using exploratory data analysis (EDA) techniques to uncover insights on pricing, availability, and geographical distribution. The project aims to identify patterns, detect outliers, and examine relationships between variables to support data-driven decision-making for hosts and travelers

## Dataset Used
-<a href="https://github.com/AvinashCodes10/Air-BnB-Python-Data-Analysis-Project/blob/main/Air%20BnB.csv">Dataset</a>

## Key KPI Questions
- How many missing values were present before and after cleaning?
- How many duplicate rows were found and removed?
- How many outliers were detected in the price column?
- What is the average price per bed across different neighborhoods?
- How does price vary across different neighborhood groups?
- How does the number of reviews correlate with price?
- How does Airbnb availability vary across different locations?
- What is the geographical distribution of Airbnb listings based on longitude and latitude?
- What is the correlation between numerical variables like price, minimum nights, number of reviews, and availability?
- How many visualizations were created, including box plots, histograms, scatter plots, and heatmaps?
- What insights were drawn from the heatmap showing variable correlations?

  - Jupyter Notebook<a href="https://github.com/AvinashCodes10/Air-BnB-Python-Data-Analysis-Project/blob/main/Air%20BnB%20Data%20Analysis%20Project.ipynb">View Jupyter Notebook</a>

  ##Process
- Data Loading & Exploration → Importing the dataset and checking its structure using .head(), .tail(), .shape(), and .describe().
- Handling Missing Values → Identifying and removing null values using .isnull().sum() and dropna().
- Removing Duplicates → Detecting and eliminating duplicate records using .duplicated() and drop_duplicates().
- Data Type Conversion → Changing data types (e.g., converting id to object) for efficient processing.
- Exploratory Data Analysis (EDA) → Performing univariate analysis (histograms, box plots) and bivariate analysis (scatter plots, bar plots).
- Feature Engineering → Creating new variables like price per bed to extract deeper insights.
- Geospatial Analysis → Visualizing Airbnb listings based on latitude and longitude to understand location distribution.
- Correlation Analysis → Using heatmaps to identify relationships between variables like price, reviews, and availability.

  ##Jupyter Notebook
  [

