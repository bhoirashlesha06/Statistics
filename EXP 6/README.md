# exp6 — Regression Model & Performance Evaluation

### Description

* Develops a linear regression model to predict **BMI** using the Pima Indians Diabetes Dataset.
* Evaluates the model using MAE, MSE, RMSE, and R² score.
* Performs residual analysis to understand prediction errors and identify possible outliers.

### Dataset

* **Pima Indians Diabetes Dataset**
* Contains medical information for 768 female patients.
* BMI is used as the continuous target variable.
* The dataset contains other medical attributes that are used as predictor variables.

### Requirements

* Python 3.8+
* numpy, pandas, matplotlib, seaborn, scikit-learn

### Install

```powershell
python -m venv .venv
.\.venv\Scripts\pip install --upgrade pip
.\.venv\Scripts\pip install numpy pandas matplotlib seaborn scikit-learn
```

### Run

```powershell
python exp6.py
```

### Outputs

* Console output showing regression model performance.
* MAE: 4.4753
* MSE: 33.9171
* RMSE: 5.8238
* R² Score: 0.2245
* Residual analysis and actual vs predicted values.

### Notes

* BMI is selected as the continuous target variable.
* The model assumes a linear relationship between the predictor variables and BMI.
* Residual analysis is used to identify prediction errors, nonlinear patterns, and possible outliers.
