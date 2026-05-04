# Credit Card Fraud Detection Project

## Project Overview

The goal of this project is to analyze fraud-related dataset, perform exploratory data analysis, apply feature engineering, train several machine learning models, and select the best-performing model for fraud detection.

The project focuses on identifying fraudulent transactions based on available transaction data and comparing different modeling approaches.

## Objectives

The main objectives of the project are:

- Load and explore fraud detection datasets
- Perform Exploratory Data Analysis (EDA)
- Identify patterns and relationships in the data
- Handle missing values, outliers, and data imbalance
- Perform feature engineering
- Train multiple machine learning models
- Compare model performance
- Select the optimal model
- Present the final results and conclusions

## Dataset

The project uses fraud detection dataset containing transaction-related information.

Dataset detailed information described in **DS_project.ipynb**, including:

- Dataset source
- Number of rows and columns
- Description of important features
- Target variable explanation
- Class distribution between fraud and non-fraud cases

## Feature Engineering

**Data_manipulation.ipynb** contains python code which performs:

- Feature engineering: handling categorials, additional columns for better training.
- Feature selection.
- Handling data imbalance
- Training a number of models to compare which model has best perfomance with the dataset.
- Dataset statistics.

## Model Training
Several machine learning models will be trained and compared, such as:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost / LightGBM

## Model Evaluation

The models will be evaluated using metrics suitable for imbalanced classification problems.

Possible evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix
- Precision-Recall Curve

Since fraud detection is usually an imbalanced classification problem, accuracy alone is not enough. Recall, precision, F1-score, and ROC-AUC are especially important.

## Technologies Used

The project uses the following technologies and libraries:

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn
- Google colab

## Usage

This project contains Google Colab notebooks and should be run from Google Colab.

The main notebooks are:

- `DS_Project.ipynb` — main project notebook for EDA, model training, evaluation, and results.
- `Data_manipulation.ipynb` — notebook for data loading, cleaning, preprocessing, and feature engineering.

To run the project:

1. Open the notebook in Google Colab.
2. Run the cells step by step.

## Project Structure

```text
CCFraudProject/
│
├── DS_Project.ipynb         # Dataset load and EDA
├── Data_manipulation.ipynb  # Training models and conclusions.
```
## License

This project is for educational purposes.

## Authors

- Daniel Igelnik
- Ranel Zissu
- Vita Preskovsky
