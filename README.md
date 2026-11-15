# Garment Worker Productivity Prediction

A Team 3 project completed as part of the UNP ML Academic Internship. This project explores operational factors associated with productivity in garment manufacturing and applies regression models to estimate actual productivity.

## Project overview

The notebook contains the end-to-end analysis and modelling workflow:

- Data inspection, quality checks, and missing-value analysis
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
| `Garment-worker-productivity-prediction.ipynb` | Main analysis and modelling notebook, including saved cell outputs |
| `garments_worker_productivity.csv` | Dataset used by the notebook |
| `requirements.txt` | Python dependencies |
| [`Garment_Worker_Productivity_Presentation.pptx`](./Garment_Worker_Productivity_Presentation.pptx) | Project presentation (PowerPoint) |

## Getting started

1. Clone this repository.
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `Garment-worker-productivity-prediction.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
4. Run the notebook from top to bottom if you want to reproduce the analysis. Existing saved outputs are included for reference.

The notebook expects the dataset file `garments_worker_productivity.csv` in the repository root.

## Team

This was a collaborative academic project completed by Team 3:

- Akula Siri
- K Jayadeva Satyavamsi
- P Harshit
- Peruri Ramya Sree

## Notes

- The notebook is committed with its saved outputs; the repository does not automatically execute notebooks on every push.
- Model results may vary with library versions and runtime environments.
- This is an educational analysis. Interpret findings within the limitations of the source dataset.
