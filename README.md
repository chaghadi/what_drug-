
# Drug Response Classifier (Multiclass Decision Tree)

This project uses a multiclass classification model to predict patient response to one of five drugs based on clinical features.

## Problem Statement

Given patient data (Age, Sex, Blood Pressure, Cholesterol), predict the drug they are most likely to respond to (Drug A, B, C, X, or Y).

## Project Structure

- `data/` – Raw dataset
- `notebooks/` – All experimentation and model development notebooks
- `scripts/` – Reusable Python scripts for processing and modeling
- `models/` – Trained and saved models
- `outputs/` – Evaluation results and visualizations

## Dataset

Source: `ML Class/drug200.csv.xls`  
Format: Excel file with clinical features and a target drug column.

## Technologies

- PySpark (MLlib)
- Pandas
- matplotlib/seaborn
- scikit-learn (for comparison only, optional)
- JupyterLab

## Objective

Train and validate a multiclass Decision Tree Classifier to support pharmaceutical decision-making by predicting likely drug response.

## Author

Charles Bernard | Pharmaceutical Engineer

# Drug Response Prediction with PySpark

This project builds a multiclass classification model to predict which drug a patient will respond to based on clinical data. The classifier was trained using PySpark's MLlib and evaluated on precision, recall, and F1 score.

## 🔬 Problem Statement

Given a dataset of patients with the following features:

- Age
- Sex
- Blood Pressure (BP)
- Cholesterol

...the task is to predict the correct **drug** the patient should be prescribed from:

- Drug A
- Drug B
- Drug C
- Drug X
- Drug Y

This is a **multiclass classification problem**.

## 📦 Setup Using Conda

If you use Conda, you can recreate the exact environment with:

```bash
conda env create -f environment.yaml
conda activate drug-predict-env




