## Wine Quality Prediction — Machine Learning Pipeline

A machine learning project predicting wine quality from physicochemical 
properties, using the Portuguese Vinho Verde dataset.

### My Contributions
This was a group project (2 members). My role covered:
- Linear Regression and Decision Tree models (full implementation)
- Model evaluation using MSE, MAE, and R²
- Baseline (Dummy model) comparison
- Feature scaling and Decision Tree tuning
- PCA for dimensionality reduction

### Project Pipeline
**Part 1 — Data Exploration & Visualisation**
- Feature distributions, correlations, and visual analysis

**Part 2 — Model Development (my work)**
- Linear Regression and Decision Tree implementation
- Model comparison and improvement
- PCA and feature importance analysis
- K-Means and Hierarchical clustering

**Part 3 — Random Forest**
- Random Forest regression with and without PCA
- Performance comparison against baseline models

### Key Finding
Random Forest outperformed all other models. Feature importance analysis 
identified alcohol content, sulphates, and volatile acidity as the 
strongest predictors of wine quality.

### Tech Stack
Python, scikit-learn, pandas, matplotlib, Jupyter Notebooks

### Dataset
UCI Wine Quality Dataset — Vinho Verde red wine, 1,599 samples, 
11 physicochemical features.
