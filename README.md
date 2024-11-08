# US Commercial Banks Default Prediction
This project analyzes and forecasts default probabilities for US commercial banks over a period of financial instability. Using asset profiles of 7,783 banks from Q4 2007 to mid-2011, it aims to identify factors that contributed to bank defaults and predict future defaults.

## Objective
The primary goal is to forecast bank defaults during the global financial crisis period, characterized by high financial volatility, by testing asset profiles and examining patterns that signal potential defaults.

## Models Used
**Logistic Regression:** Implemented to address the binary classification nature of bank defaults.

**Decision Tree:** Applied as a secondary model, providing interpretability and handling non-linearity in the data.

Both models were tuned to account for class imbalance, reflecting actual default frequencies observed in the historical dataset.

## Data
The data used in this project is confidential and cannot be shared publicly due to privacy restrictions. To experiment with the code, you may replace it with a synthetic dataset or create a similar dataset structure.

## Project Structure
**Data Preprocessing:** Steps for data cleaning, normalization, and handling missing values.
**Feature Engineering:** Methods to enhance predictive power, including asset ratios and risk-weighted indicators.
**Model Training:** Implementation of Logistic Regression and Decision Tree models with performance metrics.
**Evaluation:** Assessing model performance with metrics suitable for unbalanced datasets, such as AUC-ROC and F1-score.

## Usage
**Data Preparation:** create a similar synthetic dataset structure as given in the code.
**Run the Notebook:** Open Task 1.ipynb in Jupyter Notebook to walk through data preparation, model training, and evaluation.
**Customize Parameters:** Adjust hyperparameters as needed to experiment with model performance.

## Results
The models provide insight into critical factors contributing to bank defaults and can be further tuned or extended to predict default probabilities with higher accuracy.
