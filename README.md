# Garment Worker Productivity Prediction

An academic group project exploring operational factors associated with productivity in garment manufacturing and applying regression models to estimate actual productivity.

## Project overview

The notebook covers:
- Data quality checks and missing-value analysis
- Cleaning inconsistent categorical values
- Exploratory data analysis and visualisation
- Productivity patterns across departments, quarters, teams, and workdays
- Correlation analysis and Variance Inflation Factor (VIF) checks
- Feature engineering for operational variables
- Regression model comparison, cross-validation, and hyperparameter tuning
- An Artificial Neural Network (ANN) experiment using TensorFlow

## Models explored

Linear Regression, K-Nearest Neighbors Regressor, Support Vector Regression, Decision Tree Regressor, Random Forest Regressor, XGBoost Regressor, and a TensorFlow-based ANN.

## Repository contents

| File | Description |
| --- | --- |
| `Garment-worker-productivity-prediction.ipynb` | Main analysis and modelling notebook |
| `requirements.txt` | Python dependencies |

## Getting started

1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Obtain the original project CSV, named `garments_worker_productivity.csv`, from the course/internship source.
4. Place it in the repository root or in a folder named `data/`.
5. Open the notebook in Jupyter or Google Colab and run it from top to bottom.

**The dataset is not included** because its redistribution terms have not been established. Use the original authorised source and check its licence before sharing it.

## Academic context and attribution

This was completed as a **college group project associated with an academic internship**. The notebook represents collaborative work; it should not be interpreted as an individual project completed solely by the repository owner. Add the full team roster, mentor/institution details, and individual contributions here before presenting the repository as a final public record.

## Reproducibility notes

- The notebook's saved cell outputs have been cleared to keep the repository lightweight and encourage fresh execution.
- Model metrics may vary with library versions and runtime environments.
- The analysis is an educational exercise; findings should be interpreted in the context and limitations of the source dataset.
