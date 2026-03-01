# Revenue Optimization and Churn Prediction for a Streaming Platform

End-to-end machine learning workflow to predict user churn, evaluate revenue impact, and analyze a discount promotion experiment.

## Implementation

* Data generation, cleaning, and preprocessing
* Feature engineering (engagement score, tenure buckets, encoding, scaling)
* Models: Logistic Regression, Decision Tree, Random Forest, XGBoost
* Evaluation metrics: Accuracy, Precision, Recall, ROC-AUC
* Threshold tuning for business trade-offs
* Model interpretability using Feature Importance, Partial Dependence, SHAP, and LIME
* A/B testing with revenue comparison and Z-tests for statistical significance

## How to Run

Install dependencies:

```bash
pip install -r requirements.txt
```

Run notebooks in the following order:

1. `data_setup.ipynb`
2. `data_cleaning.ipynb`
3. `eda_analysis.ipynb`
4. `churn_prediction_model.ipynb`
5. `churn_interpretability.ipynb`
6. `ab_testing.ipynb`

## Project Structure

```
project/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── data_setup.ipynb
│   ├── data_cleaning.ipynb
│   ├── eda_analysis.ipynb
│   ├── churn_prediction_model.ipynb
│   ├── churn_interpretability.ipynb
│   └── ab_testing.ipynb
├── requirements.txt
└── README.md
```

## License

MIT License
