Phishing Website Detection Using SVM
Project Overview

📌 Introduction

Phishing attacks are among the most common cyber threats, designed to steal sensitive information such as passwords, banking details, and personal data. This project develops an intelligent phishing detection system using a Linear Support Vector Machine (SVM) model to automatically classify websites as Phishing or Legitimate based on extracted website characteristics.

🎯 Problem Statement

Internet users often struggle to identify malicious websites that imitate trusted services. Manual detection is unreliable, making automated machine learning solutions essential for improving online security.

🚀 Solution Overview

This project applies a supervised machine learning approach to analyze website features and determine whether a URL belongs to a phishing website.

The workflow includes:

Data collection and preprocessing
Feature selection
Model training using Linear SVM
Performance evaluation
Visualization of results
🏗️ System Architecture
Plain Text
Dataset
│
▼
Data Cleaning
│
▼
Feature Engineering
│
▼
Train-Test Split
│
▼
Standardization
│
▼
Linear SVM Model
│
▼
Prediction
│
├── Confusion Matrix
├── ROC Curve
└── Performance Metrics
🔍 Key Features

✅ Automated phishing website classification

✅ Handles missing and infinite values

✅ Balanced class weighting for better prediction

✅ Data standardization using StandardScaler

✅ ROC-AUC performance evaluation

✅ Visual performance analysis

🛠️ Libraries Used
Python
pandas
numpy
matplotlib
seaborn
scikit-learn
📂 Dataset Information

The project uses the PhiUSIIL Phishing URL Dataset, which contains numerous website-related attributes used to identify suspicious patterns commonly associated with phishing attacks.

🤖 Machine Learning Model
Linear Support Vector Classifier (LinearSVC)

Why SVM?

Effective for binary classification problems
Performs well with high-dimensional data
Computationally efficient
Strong generalization capability
📊 Evaluation Metrics

The model performance is measured using:

Metric	PurposePrecision	Measures prediction accuracy
Recall	Measures phishing detection capability
F1-Score	Balance between precision and recall
ROC-AUC	Overall classification quality
Confusion Matrix	Visualizes prediction results
📈 Output Visualizations
Confusion Matrix

Provides detailed insights into correct and incorrect predictions.

ROC Curve

Demonstrates the model's ability to distinguish phishing websites from legitimate websites across different thresholds.

⚙️ Installation

Clone the repository:


Install required packages:

Shell
pip install pandas numpy matplotlib seaborn scikit-learn
▶️ Running the Project
Shell
python "ML task 9.py"
🎓 Applications
Cybersecurity monitoring
URL filtering systems
Secure web browsing solutions
Enterprise security tools
Educational machine learning projects
🔮 Future Enhancements
Implement Deep Learning models
Real-time URL scanning
Browser extension integration
URL reputation checking
Deployment using Flask or Streamlit