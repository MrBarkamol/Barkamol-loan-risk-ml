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

## Notes & observations
- The dataset is moderately imbalanced, so I used `class_weight="balanced"` to reduce bias toward the majority class.
- I picked a RandomForest because it handles mixed feature types well and performs decently out of the box.
- SHAP helps interpret which features contribute most to predicted default risk.

## Resume-ready summary
Built a loan default prediction model using Python and scikit-learn; evaluated with accuracy/precision/recall/ROC-AUC and added SHAP explainability to identify key risk drivers.

## Project highlights
- End-to-end ML workflow with preprocessing, modeling, and evaluation
- Explainable model results with SHAP feature importance
- Clean, reproducible notebook for easy review

## License
MIT