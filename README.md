# Toxic Compound Classification Using Machine Learning

A learning-focused machine-learning project for classifying chemical compounds as **toxic** or **non-toxic** from high-dimensional molecular descriptor data.

## Project goal

The dataset contains more than 1,000 predictor features. The project explores a practical classification workflow:

- load and inspect the data
- handle missing values
- encode the target
- scale/select features
- create a train/test split
- train a Random Forest classifier
- evaluate classification performance
- use cross-validation as an additional stability check

## Repository contents

```text
toxicity-classification-project/
├── Untitled6.ipynb
├── data (1).csv
├── PROJECT_STATUS.md
└── README.md
```

## Model

The notebook uses a **Random Forest Classifier**.

Evaluation in the notebook includes classification-oriented metrics such as accuracy, precision, recall, F1-score, confusion matrix, and cross-validation results.

This README intentionally does not publish metric values that have not been separately verified during the portfolio cleanup.

## Tools

Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn · Jupyter Notebook

## Run

Open `Untitled6.ipynb` in Jupyter or VS Code and run the notebook from top to bottom with the CSV in the repository root.

## Deployment

No deployment is required for the current version. This repository is a modelling/analysis exercise rather than an application.

A web app would only be worth adding after the input schema, trained artifact, inference pipeline, and evaluation are cleaned into reproducible modules.

## API integration

None.

## Portfolio role

This is an **older learning project** and should remain unpinned while stronger banking, fraud, credit-risk, and deployed projects represent the main portfolio.

## Next improvements

- rename notebook and dataset files to descriptive names
- move the dataset into `data/`
- create a reproducible training script/pipeline
- verify and document final metrics
- add requirements.txt
- save the selected model only after the pipeline is reproducible
