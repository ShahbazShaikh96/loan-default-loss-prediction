# Loan Default and Loss Prediction

A two-stage machine learning project for credit-risk analytics. The workflow predicts whether a borrower is likely to default and estimates potential loss severity for defaulted loans.

## Project Goal

The project is designed around a practical lending question:

> Which loans are most likely to default, and how large could the expected loss be?

## Main Work

- cleans and prepares loan-level training and test data
- builds a default classification model
- builds a loss severity prediction model
- compares statistical and machine learning approaches
- prepares a submission file for prediction output
- documents the workflow in notebook, R Markdown, PDF, and presentation formats

## Modeling Methods

The project includes methods such as:

- Logistic Regression
- Elastic Net
- Ridge Regression
- Partial Least Squares
- Random Forest
- XGBoost

## Files

- `loan_default_loss_model.ipynb`: notebook version of the modeling workflow
- `loan-default-loss-prediction.Rmd`: R Markdown source report
- `loan-default-loss-prediction-report.pdf`: final written report
- `loan-default-loss-prediction.pptx`: presentation deck
- `Submission.csv`: prediction output file

## Reproducibility Note

The original notebook and R Markdown were built from local course datasets. Those raw source datasets are not included in this repository, so the included files should be treated as the submitted modeling artifacts and project documentation.
