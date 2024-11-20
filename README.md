# Parkinsons Disease Detection Using Machine Learning
This project aims to detect Parkinson's disease using machine learning techniques. It includes data preprocessing, feature exploration, model selection, evaluation, and deployment using a trained Support Vector Machine (SVM) model. The dataset and code are provided, along with visualizations. This project uses machine learning to classify patients as having Parkinson's disease or not, based on medical voice measurements. The goal is to create an accurate and reliable model that can assist in early diagnosis of Parkinson's disease.
# Features
Data preprocessing and visualization.
Multiple machine learning algorithms compared:
Logistic Regression, Decision Tree, Random Forest, Naive Bayes, K-Nearest Neighbors, and Support Vector Machine (SVM).
Cross-validation to ensure model generalization.
SVM chosen as the best model for deployment.
Pickle file created for model reuse.
# Dataset
The dataset contains features derived from voice recordings of individuals. Key attributes include measures of vocal frequency, amplitude, and variation, which are commonly affected by Parkinson's disease.
# Tools and Libraries
Python for coding.
pandas for data manipulation.
seaborn and matplotlib for visualization.
scikit-learn for machine learning algorithms.
pickle for model serialization.
# Usage
Install the required libraries: pip install -r requirements.txt
Run the Jupyter notebook or Python scripts to explore the data and models.
Use the trained model (model.pkl) to make predictions.
# Results
The SVM model achieved the best performance with a cross-validation accuracy of 89%. Other models like Decision Tree and Random Forest were evaluated but found to overfit.
