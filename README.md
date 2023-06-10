# Breast Cancer Prediction
### Dataset Name: Breast Cancer Wisconsin (Diagnostic) Data Set

### Dataset Definition: Predict whether the cancer is benign or malignant using features such as radius, smoothness, etc.

### Dataset Source (web address): https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data 

### Aim of the project: To determine whether a cell is a cancerous (malignant) or non-cancerous (benign) cell as a result of featurelar-based studies.

### Variable Description

Target (M = malignant, B = benign)

Ten real-valued features are computed for each cell nucleus:

- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values)
- perimeter
- area
- smoothness (local variation in radius lengths)
- compactness (perimeter^2 / area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- symmetry
- fractal dimension ("coastline approximation" - 1)

Missing attribute values: none

Class distribution: 357 benign, 212 malignant


### Contents

Preprocessing
- 1) Drop nulls and duplicates
- 2) Label Encoding
- 3) Split test and train dataset
- 4) Scaling
  - 4.1) Standard Scale
  - 4.2) Min-Max Scale
- 5) PCA
- 6) LDA
- 7) Remove Outliers
- 8) Impute
Feature Selection
- 1) Feature Selection using K-Best
- 2) Recursive Feature Elimination (RFE)
- 3) Feature Selection using Data Correlation
Machine Learning Algorithms
- Supervised Learning Algorithms
- 1) Logistic Regression
  - 1.1) Parameter Tuning for Logistic Regression
- 2) Naive Bayes 
- 3) KNN Classifier
- 4) Random Forest Classiefier
- 5) Decision Tree classifier

- 6) Evauate Recall
- Unsupervised Learning Algorithms
- 1) K-Means Clustering
  - 1.1) Parameter Tuning for K-Means Clustering
- 2) Gaussian Mixture Model (GMM) Clustering 
Multimodel Parameter Tuning
- 1) Grid Search
- 2) Random Search
- 
Pipeline
