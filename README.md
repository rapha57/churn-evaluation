# Churn Evaluation

**Practical Work - Big Data**  
Master Miage I&I - M2  
University of Lorraine / IDMC  

**Author:** Boulcourt Raphaël

## Description

Analysis and prediction of customer churn on the Telco Customer Churn dataset.  
Comparison between Logistic Regression and Random Forest, with class imbalance handling.

## Repository structure

```
.
├── churn_evaluation.ipynb
├── dataset/
│   └── churn_dataset.csv
├── README.md
└── requirements.txt
```

## Main results

- Accuracy ~ 0.78–0.79
- Feature importances and confusion matrices included
- Optimization of the number of trees (`n_estimators`)

## Installation

```bash
pip install -r requirements.txt
```

Then open the notebook in Jupyter.

> The notebook automatically loads the dataset from `dataset/churn_dataset.csv`.
