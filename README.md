# Logistic Regression Assignment: Credit Card Fraud Detection

## Overview
This project leverages Logistic Regression, a fundamental machine learning algorithm, to detect fraudulent credit card transactions. By addressing the challenges of a highly imbalanced dataset, the project showcases the application of classification metrics to assess model performance. It aims to demonstrate the effectiveness of Logistic Regression in solving binary classification problems.

## Problem Statement
Develop a machine learning model using Logistic Regression to identify fraudulent transactions within a dataset of credit card activities.

### Key Concepts
- **Logistic Regression**: A statistical model designed for binary classification tasks, such as detecting spam emails or identifying fraudulent transactions.
- **Comparison with Linear Regression**: While Linear Regression predicts continuous outcomes, Logistic Regression is tailored for categorical classifications.

## Dataset
- **Source**: Credit card transactions by European cardholders in September 2013.
- **Details**: The dataset contains 284,807 transactions over two days, with only 492 labeled as fraudulent, reflecting a significant class imbalance (fraudulent transactions account for 0.172% of the total).
- **Features**: Includes anonymized variables (V1, V2, ..., V28), along with `Time` (seconds elapsed since the first transaction), `Amount` (transaction amount), and `Class` (target variable: 1 for fraud, 0 for non-fraud).
- **Target**: A binary variable indicating whether a transaction is fraudulent (1) or not (0).

## Objectives
1. Perform exploratory data analysis (EDA) to understand feature distributions and relationships.
2. Develop and train a Logistic Regression model to classify transactions as fraudulent or non-fraudulent.
3. Evaluate the model’s performance using:
   - **Classification Report**: Precision, recall, F1-score, and support.
   - **Confusion Matrix**: Analysis of true positives, false positives, true negatives, and false negatives.

## Tools and Libraries
- **Python**: Programming language used for the project.
- **Pandas & NumPy**: Libraries for data handling and numerical operations.
- **Matplotlib & Seaborn**: Tools for creating visualizations to support EDA.
- **Scikit-learn**: Framework for implementing Logistic Regression and calculating evaluation metrics.
- **Scipy**: For statistical computations.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd logistic-regression-assignment
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook Logistic_Regression_Assignment.ipynb
   ```

## Usage
- Place the dataset (`creditcard.csv`) in the project directory.
- Open the `Logistic_Regression_Assignment.ipynb` notebook and execute the cells sequentially to:
  - Perform exploratory data analysis.
  - Preprocess the dataset to address class imbalance and prepare it for modeling.
  - Train the Logistic Regression model.
  - Evaluate results using confusion matrices and classification reports.

## Results
- **Exploratory Analysis**: Histograms and scatter plots reveal feature distributions and relationships.
- **Model Performance**:
  - **Confusion Matrix**: Details the accuracy of predictions for fraudulent and non-fraudulent transactions.
  - **Classification Report**: Summarizes precision, recall, F1-score, and support for both classes.

## Contribution
Contributions are highly encouraged! If you have suggestions or enhancements:
1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Submit a pull request describing your changes.

