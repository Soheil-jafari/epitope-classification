# epitope-classification
Classification of epitopes from high-dimensional biological data using PCA, SMOTE, and XGBoost with hyperparameter tuning and GroupKFold validation.

Epitopes Classification Using Machine Learning
This project applies machine learning techniques to classify epitopes from a high-dimensional, imbalanced biomedical dataset. The notebook includes full preprocessing, model training, and evaluation steps, using real-world data with over 1,200 features and 45,000 samples.

📁 Dataset Summary
Shape: 45,000 rows × 1,290 columns

Imbalance: Class 1 (epitopes) = 98.35%, Class -1 (non-epitopes) = 1.65%

File Used: df.csv (not included due to size/privacy)

⚙️ Tools and Libraries
Language: Python

Libraries:
pandas, numpy, matplotlib, seaborn
scikit-learn, xgboost, imblearn (for SMOTE)

🧪 ML Pipeline Summary
EDA: Visualized imbalance, checked for outliers (Z-score), and inspected feature scaling needs

Preprocessing:

No outlier removal required

Class rebalancing with SMOTE

Feature scaling for sensitive models

Models:

Logistic Regression

XGBoost (with early stopping)

Evaluation:

Accuracy, Precision, Recall, F1-Score

ROC-AUC

SHAP (optional) for interpretability

📌 Key Highlights
Tackles extreme class imbalance (~60:1) with rebalancing strategies

Explores both linear and tree-based classifiers

Jupyter-based, research-style workflow suitable for reproducibility and extension
