**Breast Cancer Classification**

**Project Overview**
This project classifies breast cancer as malignant or benign using machine learning models, including Random Forest, Gradient Boosting, and SVM. The dataset used is the **Breast Cancer Wisconsin Dataset**.

## Requirements
Install dependencies with:

pip install pandas numpy seaborn matplotlib scikit-learn tensorflow

## Steps
1. **Data Loading**: Load the dataset from `BreastCancer.csv`.
2. **Preprocessing**: Drop irrelevant columns, encode target labels, and scale features.
3. **EDA**: Visualize class distribution and feature correlations.
4. **Model Training**: Train and evaluate models (Random Forest, Gradient Boosting, SVM).
5. **Hyperparameter Tuning**: Optimize SVM parameters with GridSearchCV.
6. **Evaluation**: Analyze metrics, confusion matrix, and ROC-AUC score.

## Results
- Models are evaluated using classification reports and ROC-AUC.
- The best SVM model achieves fine-tuned performance with optimal parameters.

## Usage
Run the script to train and evaluate models:

python breast_cancer_classification.py


