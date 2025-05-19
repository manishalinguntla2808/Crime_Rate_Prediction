# Crime Rate Prediction by Area

This project aims to predict crime rates in various community areas based on historical crime data and demographic information.

## Project Objective

- Analyze the relationship between crime, demographics, and educational infrastructure.
- Predict crime rates for different community areas.
- Create visualizations to display patterns and trends.
- Build a predictive model using machine learning.

## 📊 Tools Used
- Python (Pandas, Matplotlib)
- Tableau for Data Visualization
- Jupyter Notebooks
- Git/GitHub

## 📁 Project Structure
📁 data — raw datasets
📁 notebooks — step-by-step Jupyter Notebooks
📁 tableau — dashboard and screenshots
📁 outputs — processed data

## 🧾 Datasets Used
### ChicagoCrimeData.csv
  * Source: Chicago Data Portal
  * Details: Includes type of crime, location, date, and community area.

### CensusData.csv
  * Source: U.S. Census Bureau
  * Details: Population, income, education level per community area.

### ChicagoPublicSchools.csv
  * Source: Chicago Open Data
  * Details: Information on school locations, ratings, and neighborhood areas.


## 📊 Tableau Dashboard
Interactive dashboards are created using Tableau to show:

Crimes by Community Area

Top 5 Crime Types

Crime Trend Over Time

Correlation between Crime Rate, Income, and School Ratings

## 🔎 Key Questions & Findings

  This project focused on answering the following questions using data analysis and visualizations. The insights guided the feature engineering and model development phases.

### Problem 1: Find the total number of crimes recorded in the CRIME table

🔍 Finding: The total number of crimes recorded was 533

### Problem 2: List community area names and numbers with per capita income less than 11,000

🔍 Finding: There were 4 community areas with a per capita income below $11,000. These include:

|COMMUNITY_AREA_NUMBER|COMMUNITY_AREA_NAME | COMMUNITY_AREA_NUMBER | PER_CAPITA_INCOME|
|---------------------|--------------------|-----------------------|------------------|
|25|West Garfield Park|26.0|10934|
|29|South Lawndale|30.0|10402|
|36|Fuller Park|37.0|10432|
|53|Riverdale|54.0|8201|

### Problem 3: List all case numbers for crimes involving minors (excluding children)

🔍 Finding: A total of 2 case numbers were found involving minors. These included crimes like Liquor Law Violation where the victim was identified as a minor.

['HL266884' 'HK238408']

### Problem 4: List all kidnapping crimes involving a child

🔍 Finding: Found 1 kidnapping crimes explicitly involving children. These were identified using keyword matches 'KIDNAPPING' as primary type and like "child" references in descriptions.

|Case Number|Primary Type|Description|
|-----------|------------|-----------|
|HN144152|KIDNAPPING|CHILD ABDUCTION/STRANGER	|
