# ds-project

Credit Card Fraud Detection
🧾 Overview
This project aims to build a machine learning model to detect fraudulent credit card transactions using a real-world dataset. Fraud detection is a critical problem in financial systems, where identifying suspicious behavior quickly and accurately can prevent massive financial losses.

📁 Dataset
Source: Kaggle Credit Card Fraud Detection Dataset

Size: 284,807 transactions

Features:

30 total columns

Time, Amount, and 28 anonymized PCA-transformed variables (V1 to V28)

Target column: Class (0 = Legit, 1 = Fraud)

📌 Objectives
Understand the distribution of fraud vs. legitimate transactions.

Preprocess data for better model performance.

Train and evaluate machine learning models to identify fraudulent transactions.

Handle extreme class imbalance effectively.

🧪 Models Used
Logistic Regression

Decision Tree

Random Forest

XGBoost / LightGBM (optional)

Evaluation with metrics: Precision, Recall, F1-Score, ROC-AUC

📉 Techniques Applied
Data preprocessing and feature scaling

Handling class imbalance using:

Undersampling

Oversampling (SMOTE)

Confusion matrix and ROC curve visualizations

🔧 Requirements
Python 3.x

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn

To install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
🚀 Getting Started
Clone the repository or download the notebook.

Run credit card fraud detection model.ipynb in Jupyter Notebook or Google Colab.

📊 Results
High Recall achieved on fraudulent transactions.

Precision-Recall trade-off carefully managed to reduce false negatives.



👤 Author
Name: Aryan
Project Type: Academic / Research
Tools Used: Python, Jupyter Notebook, Scikit-learn

📜 License
This project is for academic and educational purposes.
 








