# exp8 — Clustering & Dimensionality Reduction

### Description

* Applies unsupervised learning techniques to discover patterns in the Pima Indians Diabetes Dataset.
* Uses **K-Means Clustering** to group patients based on similarities in their medical attributes.
* Uses **PCA (Principal Component Analysis)** to reduce the dimensionality of the dataset and visualize the clusters.
* Evaluates the clusters using the Elbow Method and Silhouette Score.

### Dataset

* **Pima Indians Diabetes Dataset**
* Contains medical information for 768 female patients.
* The `Outcome` variable indicates diabetes status.
* `Outcome` is excluded during clustering and used later to compare the discovered clusters with known diabetes categories.

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
python exp8.py
```

### Outputs

* Elbow Method plot for selecting the number of clusters.
* Silhouette Score for evaluating cluster quality.
* PCA visualization of the clusters.
* Selected number of clusters: `k = 3`
* Silhouette Score: `0.1448`
* PCA loading analysis for the first two principal components.

### Notes

* K-Means clustering is performed on standardized numerical features.
* PCA is used to represent the high-dimensional dataset in two dimensions.
* The discovered clusters show some overlap and do not perfectly match the known diabetes Outcome categories.
