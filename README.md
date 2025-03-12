# 🐴 Donkey Weight Estimation Using Regression Models

This project develops machine learning models to estimate the weight of donkeys in rural Kenya using measurable physical characteristics. The goal is to build reliable predictive models that can assist in animal health monitoring, especially in regions where resources are limited.


## Dataset Overview

- **Source**: Real-world field data collected in rural Kenya
- **Total Records**: 544 donkeys
- **Features**:
  - Numerical: Length, Girth, Height, BCS (Body Condition Score), Age
  - Categorical: Sex, Area


## Project Objectives

- Clean and preprocess the dataset
- Detect and remove outliers
- Build and evaluate various linear regression models
- Incorporate both numerical and categorical features
- Compare model performance using MSE
- Visualize learning curves and prediction outputs

## Machine Learning Concepts Applied

- Python Libraries: TensorFlow, Keras, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- Linear Regression (univariate and multivariate)
- One-hot Encoding for categorical variables
- Model training with TensorFlow/Keras
- Learning curve plotting
- Mean Squared Error (MSE) for evaluation
- Feature importance analysis
- Handling mixed data types (categorical + numerical)


## Model Evaluation

- Univariate models were first built on individual predictors (Length, Girth, Height, BCS, etc.).
- Multivariate models combined top features.
- A model with all numerical features outperformed others with the **lowest MSE**.
- Incorporating **categorical features using one-hot encoding** provided additional performance gains.


## Key Insights

- **Girth** and **Height** were among the most predictive features for estimating donkey weight.
- **Outlier removal** significantly improved model performance.
- **Multivariate models** that included both categorical and numerical features yielded better predictions.

## Sample Visualizations

- Scatter plots with regression lines
- Model learning curves
- Bar plots comparing MSE across models

## Conclusion

Through systematic feature selection, model evaluation, and interpretation, this project successfully demonstrates how linear regression can be applied to a real-world problem involving animal health in resource-constrained environments. It emphasizes the importance of data cleaning, one-hot encoding, and evaluation metrics in building reliable regression models.


