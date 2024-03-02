# Advertising Sales Prediction

## Overview
This project aims to predict sales based on advertising data using machine learning techniques. It analyzes the relationship between advertising spending across different media channels (TV, radio, newspaper) and the resulting sales figures.

## Dataset
The dataset is sourced from [Advertising Sales Dataset](https://www.kaggle.com/datasets/yasserh/advertising-sales-dataset) on Kaggle. It contains information about advertising budgets for TV, radio, and newspaper, along with corresponding sales figures.

## Files
- **notebook.ipynb**: Jupyter Notebook containing the code and analysis for the project.
- **data.csv**: CSV file containing the dataset used in the analysis.

## Dependencies
- Python 3
- Jupyter Notebook
- Libraries: pandas, scikit-learn, seaborn, matplotlib

## Usage
1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd Advertising-Sales-Prediction`
3. Install dependencies: `pip install -r requirements.txt`
4. Open and run the Jupyter Notebook: `jupyter notebook notebook.ipynb`

## Results
- The analysis includes exploratory data analysis, feature engineering, model training, and evaluation.
- Models used: Multiple Linear Regression, Polynomial Regression.
- Evaluation metrics: Mean Absolute Error and R-squared.

## Conclusion
- The Polynomial Regression model showed improved performance compared to Multiple Linear Regression, with a higher R-squared value indicating better fit to the data.
