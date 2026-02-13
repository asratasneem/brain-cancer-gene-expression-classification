# Brain Cancer RNA-Seq Classification Using Machine Learning

## Overview
This project implements a machine learning-based classification pipeline for brain cancer using RNA-seq gene expression data. The workflow integrates preprocessing, dimensionality reduction, supervised learning, and ensemble modeling to improve predictive performance.

## Objectives
- Perform exploratory data analysis (EDA) on high-dimensional gene expression data
- Apply dimensionality reduction techniques
- Train multiple classification models
- Evaluate model performance using standard metrics
- Improve predictive accuracy using ensemble methods

## Methods

### Data Processing
- Data cleaning and normalization
- Target distribution analysis
- Feature scaling

### Dimensionality Reduction
- Principal Component Analysis (PCA)

### Machine Learning Models
- Decision Tree
- Support Vector Machine (SVM)
- Random Forest
- Majority Vote Ensemble Classifier

### Model Evaluation
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Key Findings
- Random Forest demonstrated the highest standalone performance.
- Ensemble modeling improved classification robustness.
- Dimensionality reduction improved computational efficiency while retaining biological signal.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Reproducibility
To reproduce results:
```bash
pip install -r requirements.txt
python src/classification_pipeline.py
