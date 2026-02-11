# Loan Default Risk Predictor (Beginner ML Project)

A beginner-friendly, end-to-end tabular ML project that predicts loan default risk and includes model explainability.

## What this project demonstrates
- Data loading and basic EDA
- Preprocessing (missing values + categorical encoding)
- Model training and evaluation
- Explainability with SHAP

## Dataset
This project uses the **German Credit (credit-g)** dataset from OpenML.

## How to run
1. Create a virtual environment (optional)
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook
   ```
4. Run `loan_default_risk.ipynb`

## Results
The notebook reports model metrics (accuracy, precision, recall, ROC-AUC) and includes a SHAP summary plot for feature importance.

## License
MIT