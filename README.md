# Data Analysis Project

This project explores and analyzes a dataset of demographic and income-related attributes, aiming to understand patterns and insights about income distribution across various demographic groups.

## Project Overview
The primary goal of this project is to analyze demographic data to uncover patterns that distinguish individuals who earn more than $50K annually from those who earn less. The analysis focuses on data cleaning, descriptive statistics, and exploratory data analysis (EDA) to provide insights and visualize relationships within the dataset.

## Dataset
- **Source**: The dataset is stored in a CSV file located in the `data` folder.
- **Description**: The dataset includes demographic and financial information with 15 columns (features), listed below.

### Data Columns (Features)
1. **age**: Age of the individual (numerical)
2. **workclass**: Employment type (categorical)
3. **fnlwgt**: Final weight - represents the number of people the census believes the entry represents (numerical)
4. **education**: Highest level of education attained (categorical)
5. **education-num**: Education level as a numerical representation (numerical)
6. **marital-status**: Marital status of the individual (categorical)
7. **occupation**: Type of occupation (categorical)
8. **relationship**: Relationship status (categorical)
9. **race**: Race of the individual (categorical)
10. **sex**: Gender (categorical)
11. **capital-gain**: Capital gains (numerical)
12. **capital-loss**: Capital losses (numerical)
13. **hours-per-week**: Hours worked per week (numerical)
14. **native-country**: Country of origin (categorical)
15. **income**: Classification label indicating if income is >$50K or <=$50K (categorical)

## Summary of Findings
After analyzing the data, a key insight observed is:
- **Individuals who are educated, married, white, older males have a higher probability of earning above 50K in income**.

## Project Structure
The project files are organized as follows:
- `data/`: Contains the CSV file with the dataset.
- `notebooks/`: Jupyter Notebook containing the full data analysis, including:
  - **Data Cleaning**: Handling missing values, encoding categorical variables, and transforming data as necessary.
  - **Descriptive Analysis**: Generating summary statistics for each feature.
  - **Exploratory Data Analysis (EDA)**: Visualizations and analysis to identify patterns, correlations, and other insights.

## Analysis Methods
- **Descriptive Statistics**: To understand the distribution and summary statistics of each feature.
- **Data Cleaning**: To prepare the dataset for analysis by addressing missing values and outliers.
- **Exploratory Data Analysis (EDA)**: Using visualizations (e.g., histograms, box plots, and bar charts) to examine relationships between features and the target variable (`income`).

## Conclusion
The analysis reveals that specific demographic characteristics are associated with income levels above $50K. This insight can be useful for developing targeted strategies for economic studies, policy development, or further predictive modeling.

## Requirements
The following Python libraries are required to run the notebook:
- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`

## Usage
1. Clone the repository.
2. Install the required libraries.
3. Run the Jupyter Notebook in the `notebooks/` folder to explore the full analysis.

