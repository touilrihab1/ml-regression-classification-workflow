# ML Regression & Classification Workflow

This repository demonstrates an end-to-end workflow for supervised machine learning tasks, including **regression** and **classification**.

The project showcases:
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Model building and evaluation
- Hyperparameter tuning with GridSearchCV
- K-fold cross-validation
- Performance visualization with plots and metrics

---

## Notebooks

1. **Regression Notebook**:  
   - Dataset: Public regression dataset (e.g., Boston Housing or any similar dataset)  
   - Models used:
     - Linear Regression
     - Decision Tree Regression
     - Support Vector Regression
     - k-Nearest Neighbors Regression
   - Steps:
     - Train-test split
     - Scaling
     - Initial model evaluation
     - Hyperparameter optimization
     - K-fold cross-validation
     - Comparison of models with R², MSE, MAE
     - Visualizations: Parity plots, error histograms, bar plots

2. **Classification Notebook**:  
   - Dataset: Public classification dataset (e.g., Titanic Survival, Iris, or similar)  
   - Models used:
     - Logistic Regression
     - Decision Tree Classifier
     - Support Vector Machine (SVM)
     - k-Nearest Neighbors (kNN)
   - Steps:
     - Train-test split
     - Scaling
     - Initial model evaluation
     - Hyperparameter optimization
     - K-fold cross-validation
     - Comparison of models using accuracy
     - Confusion matrices and visualizations

---

## Key Features

- Comparison of multiple ML models on the same dataset
- Full evaluation with metrics and plots
- Analysis of model performance before and after hyperparameter tuning
- K-fold cross-validation to ensure model robustness
- Public datasets used, fully reproducible

---

## Technologies & Libraries

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Optional: Jupyter / Google Colab

---

## How to Run

1. Open the notebooks in Google Colab or Jupyter Notebook.
2. Install required libraries (if needed):
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
