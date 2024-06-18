# German-Credit-Dataset-Analysis
This repository contains the Jupyter Notebook for analyzing the German Credit Dataset. The project focuses on performing Exploratory Data Analysis (EDA), data cleaning, and identifying correlations within the dataset.

## File Description

- **German Credit Dataset.ipynb**: This is the main Jupyter Notebook file containing all the code, visualizations, and explanations for the project tasks.

## Requirements

To run the notebook, you will need the following Python packages:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `jupyter`

The dataset was analyzed to identify trends and patterns, with correlation analysis revealing that the Credit amount had a maximum correlation of 0.62 with another feature, indicating a moderate positive relationship. Missing values in the Saving accounts and Checking account columns were handled using the fillna() function, ensuring no null values remained. A heatmap was used to visualize correlations, confirming the highest correlation of 0.62 for Credit amount. Outliers in the Credit amount column were detected using a boxplot, identifying extreme values that may affect analysis. These preprocessing and analysis steps ensured the dataset was clean and suitable for further analysis or predictive modeling, providing valuable insights into feature relationships.
