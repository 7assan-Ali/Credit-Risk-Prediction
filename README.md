# Credit Risk Prediction

Classification workflow using the Statlog German Credit dataset to demonstrate practical credit-risk modeling.

## Models
Logistic Regression · Random Forest · Gradient Boosting

## Metrics
Accuracy · Precision · Recall · F1 · ROC-AUC

## Dataset
https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/credit.csv

The training script downloads the dataset automatically. The project is educational and does not represent a real credit decision system.

## Run
```bash
python -m venv .venv
.venv\\Scripts\\Activate.ps1
pip install -r requirements.txt
python src/train.py
```

## Methodology
Categorical variables are one-hot encoded and numeric variables are imputed/scaled inside a Pipeline. The train/test split occurs before preprocessing is fitted.

## Author
Hassan Ali — Computer Science student focused on Machine Learning and AI Engineering.
