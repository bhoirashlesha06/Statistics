# exp7 — Classification Models & Performance Evaluation

### Description

* Builds a supervised classification model to predict diabetes outcomes using the Pima Indians Diabetes Dataset.
* Implements Logistic Regression to classify patients as diabetic or non-diabetic.
* Evaluates the model using accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC.

### Dataset

* **Pima Indians Diabetes Dataset**
* Contains medical information for 768 female patients.
* Target variable:

  * `Outcome = 0` → Non-diabetic
  * `Outcome = 1` → Diabetic

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
python exp7.py
```

### Outputs

* Console summary of classification model performance.
* Accuracy: 0.7078
* Precision: 0.6000
* Recall: 0.5000
* F1-Score: 0.5455
* ROC-AUC: 0.8130
* Confusion matrix and classification evaluation results.

### Notes

* Logistic Regression is used as the classification model.
* A stratified train-test split and suitable preprocessing are applied.
* ROC-AUC measures the model's ability to distinguish between diabetic and non-diabetic patients.
* Recall is particularly important for identifying actual diabetic patients and reducing false negatives.
