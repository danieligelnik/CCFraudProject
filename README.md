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

The project uses dataset containing detailed credit cards transaction information.

Dataset's information, statistical evaluation and graphical presentations are described in **DataSet_analysis_EDA.ipynb**, including:

- Dataset source
- Number of rows and columns
- Description of important features
- Target variable explanation
- Class distribution between fraud and non-fraud cases
- Correlations between different features
- Feature importance

## Feature Engineering

**Training.ipynb** contains python code which performs:

- Feature engineering: handling categorials, additional columns for better training.
- Feature selection: features found not contributing to the model's training are removed.
- Handling data imbalance: since the dataset is heavaly imbalanced additional handling was added to improve model's training.
- Training a number of models to compare which model has the best perfomance with the dataset, especially recall score.

## Model Training
Several machine learning models are trained and compared, such as:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost / LightGBM

## Model Evaluation

The models are evaluated using metrics suitable for imbalanced classification problems.

Possible evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix
- Precision-Recall Curve

Since fraud detection is usually an imbalanced classification problem, accuracy alone is not enough. Recall, precision, F1-score, and ROC-AUC are especially important.

## Model testing

The chosen model XGBoost is tested with the test portion of the dataset in **Test_model.ipnb**

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

- `DataSet_analysis_EDA.ipynb` — main project notebook for EDA, model training, evaluation, and results.
- `Training.ipynb` — notebook for data loading, cleaning, preprocessing, and feature engineering.
- `Test_model.ipynb` - nobebook with test part of the dataset to test chosen model.
- `help_functions.ipynb` - helper functions used by all other notebooks.

To run the project:

1. Open the notebook in Google Colab.
2. Run the cells step by step.

## Project Structure

```text
CCFraudProject/
│
├── DataSet_analysis_EDS.ipynb         # Dataset load and EDA
├── Training.ipynb                     # Training models and conclusions.
├── Test_model.ipynb                   # Testing model on the test part of the dataset.
├── help_functions.ipynb               # Helper functions.
```
## License

This project is for educational purposes.

## Authors

- Daniel Igelnik
- Ranel Zissu
- Vita Preskovsky
