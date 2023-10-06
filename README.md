<div align="center">
  <h1>House Price Estimation</h1>
</div>

## Predicting Property Values in King County, Seattle

Welcome to our House Price Estimation project repository. Here, we harness the power of machine learning to forecast property sale prices in King County, Seattle. Our aim is to provide valuable insights and precise predictions for the dynamic real estate market.

## Project Inspiration

This endeavor is driven by the desire to build a robust model capable of accurately estimating property prices. Such a model has practical implications for both buyers and sellers, enabling them to make well-informed decisions and gain a deeper understanding of property valuation.

## Project Overview

This project unfolds in the following phases:

- **Data Refinement and Preprocessing:** Ensuring data integrity and consistency.
- **Exploratory Data Analysis (EDA):** Uncovering hidden patterns and gaining insights.
- **Feature Selection:** Identifying the most influential features.
- **Model Training and Assessment:** Employing Linear Regression, Decision Tree, Random Forest (degree 2 and 3), and fine-tuning model hyperparameters.
- **Comparative Model Analysis:** Drawing conclusions based on model performance and the insights we derive.

## Dataset Overview

Our dataset comprises property sale records spanning from May 2014 to May 2015, encompassing a diverse set of features including bedrooms, bathrooms, square footage, condition, grade, and more.

## Key Features

- Thorough data analysis and insightful visualizations.
- Multiple machine learning models for precision predictions.
- Rigorous hyperparameter optimization for model excellence.

## Technologies Utilized

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
## Project Workflow

1. Import Data and Assess Dataset Dimensions
2. Handle Missing Data
3. Investigate Column Types and Statistic Summaries
4. Execute Univariate Analysis
5. Perform Bivariate Analysis
6. Eliminate Redundant Columns
7. Encode Categorical Variables
8. Partition Data into Training and Testing Sets
9. Standardize Features
10. Train and Evaluate Models (Linear Regression, Decision Tree, Random Forest)
11. Fine-Tune Model Parameters for Optimization
12. Scrutinize and Analyze Model Performance
13. Determine the Optimal Model for Property Price Estimation

## In-Depth Data Exploration (IDE)

Immerse yourself in data distributions, correlations, and the visualization of intriguing data patterns. Visualizations include histograms, scatter plots, and correlation heatmaps.

## Model Training and Evaluation

Efficiently implement and train machine learning models, optimize hyperparameters, and assess performance using R-squared and RMSE metrics.

## Outcomes

### Histogram
 <p align="center">
  <img src="https://github.com/AyushSrivastava987/House_Price_Prediction/blob/main/Image/Histogram.png" alt="KPI Banner" width="1000" />
</p>
### Distribution Variations
 <p align="center">
  <img src="https://github.com/AyushSrivastava987/House_Price_Prediction/blob/main/Image/Variation%201.png" alt="KPI Banner" width="1000" />
</p>
 <p align="center">
  <img src="https://github.com/AyushSrivastava987/House_Price_Prediction/blob/main/Image/Variation%202.png" alt="KPI Banner" width="1000" />
</p>
 <p align="center">
  <img src="https://github.com/AyushSrivastava987/House_Price_Prediction/blob/main/Image/Variation%203.png" alt="KPI Banner" width="1000" />
</p>
### Model Effectiveness

After rigorous scrutiny and model assessment:

- **Linear Regression:** R2-Score: 0.6807, RMSE: 203796.0159
- **Decision Tree:** R2-Score: 0.7043, RMSE: 196142.2947
- **Random Forest:** R2-Score: 0.8710, RMSE: 129540.4012
- **Polynomial Regression (Degree 2):** R2-Score: 0.7869, MSE: 29888549258.824467
- **Polynomial Regression (Degree 3):** R2-Score: -6250056939565539.0, MSE: 8.76672289925631e+26

## Concluding Remarks

The Random Forest model emerges as the top-performing model for estimating property prices, achieving a remarkable R2-Score of 0.8710 and a minimal RMSE. Our project's extensive analysis and well-executed machine learning techniques provide invaluable insights into the real estate market. We invite you to delve into the Jupyter notebook for an in-depth exploration of this project.
