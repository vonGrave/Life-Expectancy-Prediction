# Life Expectancy Prediction Model

## Project Overview
This project implements a linear regression model to predict life expectancy based on various socio-economic and health factors. The model analyzes data from different countries, considering factors such as mortality rates, disease prevalence, healthcare spending, and economic indicators.

## Dataset Description
The dataset (Life_Expectancy_Data.csv) contains information about various factors affecting life expectancy, including:
- Country and Year
- Development Status (Developing/Developed)
- Adult Mortality rates
- Infant deaths
- Alcohol consumption
- Healthcare expenditure
- Disease-related factors (Hepatitis B, Measles, etc.)
- Economic factors (GDP, Population)
- Social factors (Schooling, Income composition)

## Technical Details
### Libraries Used
- numpy
- pandas
- matplotlib
- seaborn
- statsmodels
- sklearn

### Model Performance
The linear regression model achieved:
- Training R² score: 0.85
- Test R² score: 0.84
- Mean Absolute Error: 2.8 years
- Mean Absolute Percentage Error (MAPE): 4.3%
- Root Mean Square Error (RMSE): 3.73 years

## Key Findings
1. The model demonstrates good predictive power with comparable performance on both training and test sets
2. Average prediction error is within 2.8 years of actual life expectancy
3. Model predictions are within 4.3% of actual values on average
4. No significant overfitting or underfitting observed

## Running the Analysis
1. Ensure all required libraries are installed
2. Place the Life_Expectancy_Data.csv file in the working directory
3. Run the Jupyter notebook LifeExpectancy.ipynb

## Model Validation
- Train-test split: 70-30 ratio
- Model performance metrics calculated on both training and test sets
- Comparable performance metrics between training and test sets indicate good generalization

## Future Improvements
- Feature engineering to capture interaction effects
- Implementation of non-linear models
- Cross-validation for more robust performance estimation
- Hyperparameter tuning
- Analysis of feature importance

## Requirements
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- StatsModels
