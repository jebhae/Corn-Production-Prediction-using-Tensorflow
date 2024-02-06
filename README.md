# Corn Production Prediction with TensorFlow

## Description
This project implements machine learning models for predicting corn production using TensorFlow. The included models are Linear Regression, Random Forest, and Gradient Boosting Regressor.

## Features
- Utilizes TensorFlow for machine learning.
- Implements three regression models: Linear Regression, Random Forest, and Gradient Boosting Regressor.

## Dependencies
- Python 3.x
- TensorFlow
- Scikit-learn
- Pandas

## Installation
1. Clone the repository.

## Data
The code relies on the `corn_data.csv` file, which should contain columns for features and the target variable (Yield). The dataset is taken from Kaggle https://www.kaggle.com/datasets/japondo/corn-farming-data

##**Preprocessing**
- Basic data exploration techniques
- Data visualization on how the gender and age categories affect the target variable
- Correlation heatmap of numerical variables.
- Label encoded the categorical features.
- Selected important features that affect the Yield of corn using correlation matrix.
- Train test split of data for model building

## Models
### Linear Regression
- Implemented using TensorFlow's linear regression model.
- Adjust hyperparameters in `train_linear_regression.py`.

### Random Forest
- Implemented using TensorFlow's Decision Forests.
- Adjust hyperparameters in `train_random_forest.py`.

### Gradient Boosting Regressor
- Implemented using TensorFlow's Gradient Boosting.
- Adjust hyperparameters in `train_gradient_boosting.py`.

## Results
- Provide insights into the performance of each model.
- Include metrics such as Mean Squared Error (MSE).
- It is found that Gradient Boosting regressor is efficient with less MSE for this particular problem
- Further this can be extended by hyperparameter tuning which result in better prediction model

## License
This project is licensed under the Apache License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
- Thanks to the TensorFlow and Scikit-learn communities.

## Contact Information
For questions or feedback, contact Jebha Emmanuvel at jebhaemmanuvel@gmail.com.

