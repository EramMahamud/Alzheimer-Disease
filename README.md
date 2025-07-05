Alzheimer’s Disease Prediction with Explainable AI (SHAP & LIME)
This Jupyter Notebook demonstrates a machine learning pipeline for predicting Alzheimer's disease using patient data. It incorporates explainable AI (XAI) techniques such as SHAP and LIME to interpret model predictions and identify important features contributing to Alzheimer’s classification.

🧠 Project Overview
Objective: Predict the presence of Alzheimer's disease and explain model predictions using SHAP and LIME.

Dataset: Medical dataset related to Alzheimer’s disease with features including cognitive test results, demographic information, and biomarkers.

Models Used: Logistic Regression, Random Forest, XGBoost (etc.)

Explainability Tools:

SHAP (SHapley Additive exPlanations)

LIME (Local Interpretable Model-agnostic Explanations)

📁 Contents
Data preprocessing (missing values, encoding, normalization)

Model training and evaluation

Feature importance visualization

Explanation of predictions using SHAP and LIME

Visualizations: summary plots, force plots, etc.

🧰 Requirements
Install the following packages before running the notebook:

bash
Copy
Edit
pip install pandas numpy scikit-learn xgboost shap lime matplotlib seaborn
📊 How to Run
Clone this repository or open the .ipynb file in Jupyter Notebook, JupyterLab, or Google Colab.

Ensure the dataset is loaded correctly in the notebook.

Run each cell sequentially:

Preprocessing → Training → Evaluation → SHAP & LIME analysis.

📌 Key Features
Trains ML models for Alzheimer’s classification

Evaluates model performance using accuracy, confusion matrix, etc.

Uses SHAP and LIME for model interpretation

Provides clear visualizations for insights

📷 Example Visuals
SHAP Summary Plot

LIME Local Explanation

Feature Importance Bar Graph

💡 Use Cases
Medical decision support systems

Trustworthy and interpretable AI in healthcare

Educational purposes for understanding model explainability

📬 Contact
For any questions or collaboration inquiries, please contact:

Eram Mahamud
Email: eram.mahamud@students.mq.edu.au
LinkedIn: https://www.linkedin.com/in/eram-mahamud/?originalSubdomain=bd

