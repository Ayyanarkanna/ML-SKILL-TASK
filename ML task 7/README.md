#Decision Tree Classifier

📌 Project Overview
This project uses Machine Learning to identify whether a URL is legitimate or a phishing URL. A Decision Tree Classifier is trained using numerical features from the PhiUSIIL Phishing URL Dataset to classify URLs and evaluate the model's performance.

🎯 Objectives
Detect phishing URLs using Machine Learning.
Preprocess and prepare the dataset.
Train a Decision Tree Classifier.
Visualize the decision tree and confusion matrix.
Evaluate the model using performance metrics.
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Google Colab / Jupyter Notebook
📂 Dataset
Dataset: PhiUSIIL Phishing URL Dataset

The dataset is loaded from PhiUSIIL_Phishing_URL_Dataset.csv.

It contains URL-related features and a target column named label. The notebook maps label 0 to the positive class representing phishing and other labels to the negative class representing legitimate URLs.

⚙️ Project Workflow
1. Data Loading
Import the required Python libraries.
Load the dataset using Pandas.
Check the dataset shape, columns, missing values, and label distribution.
2. Data Preprocessing
Remove records with missing target labels.
Select numerical features for model training.
Replace infinite values with missing values.
Fill missing feature values using column medians.
3. Train-Test Splitting
Split the dataset into 80% training data and 20% testing data.
Use stratified sampling to maintain class proportions.
Set random_state=42 for reproducibility.
4. Model Training
Train a Decision Tree Classifier with the following settings:

Maximum depth: 5
Class weighting: Balanced
Random state: 42
5. Visualization
Display the trained decision tree.
Generate a confusion matrix to compare actual and predicted classes.
6. Model Evaluation
The model is evaluated using:

Accuracy: Overall proportion of correct predictions.
Precision: Proportion of predicted phishing cases that are actually phishing.
Recall: Proportion of actual phishing cases correctly identified.
F1-score: Balance between precision and recall.
Specificity: Proportion of legitimate cases correctly identified.
▶️ How to Run the Project
Open Google Colab or Jupyter Notebook.
Upload MLTASK6.ipynb.
Upload PhiUSIIL_Phishing_URL_Dataset.csv to the appropriate location.
Ensure the dataset path in the code matches its actual location.
Run all notebook cells in order.
Review the decision tree visualization, confusion matrix, and evaluation metrics.
📊 Expected Output
Dataset information and label counts.
Training and testing record counts.
Decision tree visualization.
Actual and predicted labels.
Confusion matrix.
Accuracy, precision, recall, F1-score, and specificity.
The actual performance values depend on the dataset and the execution results.
