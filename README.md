# Project Regression - Sales Prediction Project

This project leverages machine learning to predict sales outcomes based on advertising campaign data. Using Linear and Polynomial Regression models, it analyzes the relationships between various advertising inputs and resulting sales figures.

## Project Structure
1. **Data Loading and Preprocessing**
   - Loads a dataset (`SalesPrediction.csv`) with advertising metrics.
   - Preprocesses data by encoding categorical variables (One-Hot Encoding for `Influencer` type) and handling missing values.
   - Splits data into training and test sets (70-30 split).

2. **Feature Engineering**
   - Standardizes features using `StandardScaler`.
   - Generates polynomial features for non-linear modeling.

3. **Model Training and Evaluation**
   - Trains Linear Regression and Polynomial Regression models.
   - Evaluates model performance using metrics like R-squared.

## Installation
Ensure you have Python 3.6+ and the following libraries:
```bash
pip install pandas numpy scikit-learn
```

## Usage
1. **Run the Notebook**: Execute each cell sequentially to preprocess data, train models, and view results.
2. **Customize Parameters**: Modify model parameters like `degree` for Polynomial Regression to test different configurations.

## Results
The model outputs predicted sales values and evaluates performance, providing insights into the impact of different advertising features on sales.

## License
This project is for educational purposes. 
