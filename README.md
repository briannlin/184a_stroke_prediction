# CS 184A - Stroke Prediction

## Set-up instructions
1. Clone this GitHub repository.
2. Install dependencies: `pip install matplotlib seaborn numpy pandas scikit-learn imblearn`
3. Run all cells in `stroke_prediction.ipynb`
   - NOTE: Random forest grid-search will take a long time due to a lot of hyperparameter searching. Recommended to skip running this particular cell if time is limited.


## Files Overview
### 1. Data
 - `data/healthcare-dataset-stroke-data.csv` - Original stroke patients dataset.
 - `data/train.csv` - Synthetic stroke patients dataset generated by Kaggle, using the same distribution as healthcare-dataset-stroke-data.csv.

### 2. Jupyter Notebook
 - `stroke_prediction.ipynb` - Jupyter notebook containing the project work. Contains scripts for dataset visualization, dataset pre-processing, model evaluation, SMOTE sampling, grid-search cross-validation + hyperparameter tuning, and model exploration. Contains run output of all cells as well.
 - `stroke_prediction.html` - HTML version of the Jupyter Notebook, with code + cell ouputs.

### 3. Best Classifier Models
- `models/log_reg_best_model` - Best logistic regression model (highest valdatiion performance after hyperparameter tuning).
- `models/dt_best_model` - Best decision tree model (highest valdatiion performance after hyperparameter tuning).
- `models/rf_best_model` - Best random forest model (highest valdatiion performance after hyperparameter tuning).
- `models/knn_best_model` - Best K-nearest neighbors model (highest valdatiion performance after hyperparameter tuning).
- `models/mlp_best_model` - Best multi-layer perception model (highest valdatiion performance after hyperparameter tuning).