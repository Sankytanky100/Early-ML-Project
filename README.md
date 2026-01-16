# US Census Income Prediction (ML Pipelines)

Build an end-to-end, production-style machine-learning pipeline that predicts whether an individual's income exceeds **$50K** using the UCI Adult dataset. The notebook is designed to be **clear, reproducible, and interview-ready**, with clean preprocessing, evaluation, and model inspection.

## What this project demonstrates

- **Data ingestion & cleaning** from a public dataset
- **Missing-value handling** and categorical encoding with `ColumnTransformer`
- **Model comparison** (Decision Tree stump, AdaBoost, Gradient Boosting)
- **Hyperparameter tuning** with `GridSearchCV`
- **Evaluation** using accuracy, precision, recall, F1, and confusion matrix
- **Feature importance** inspection for interpretability

## Files

- `US_Census_Income_Prediction_ML_Pipelines.ipynb` — the main notebook containing all analysis and pipelines.
- `requirements.txt` — minimal dependencies to run the notebook.

## Quickstart

1. Create a virtual environment (optional but recommended).
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Launch the notebook:

```bash
jupyter notebook US_Census_Income_Prediction_ML_Pipelines.ipynb
```

## Dataset

The notebook uses the [UCI Adult dataset](https://archive.ics.uci.edu/ml/datasets/adult) and downloads it directly from the original public URL. Missing values are represented by `?` and are handled during preprocessing.

## Notes for reviewers

This notebook emphasizes **clean ML engineering practices**: modular preprocessing, consistent evaluation, and documented steps. It is intentionally structured to be readable by recruiters and hiring managers who want to see both the methodology and code quality.
