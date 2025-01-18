Conformalized Prediction of Inpatient Medication in Parkinson's Disease

This repository contains two implementations of conformal prediction for zero-inflated data:

## conformal_pd.ipynb
Initial Version

## conformal_pd_new.py
- Uses scikit-learn style API (XGBClassifier/XGBRegressor)
- More intuitive interface
- Coverage: 0.845, Avg interval length: 0.139

## conformal_pd_new_api.py
- Uses native XGBoost API (xgb.train with DMatrix)
- More low-level control
- Coverage: 0.841, Avg interval length: 0.156

Both implementations achieve similar results with slight differences in implementation approach.