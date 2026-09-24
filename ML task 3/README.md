# ML-Sales-2-Task
Customer Segmentation using RFM and K-Means
📌 Project Overview

This project performs customer segmentation using machine learning techniques.

The customers are grouped based on their purchasing behavior using RFM analysis:

Recency – How recently a customer made a purchase
Frequency – How often a customer makes purchases
Monetary – How much money a customer spends

After calculating the RFM values, K-Means Clustering is used to divide customers into different groups.

🛠️ Technologies Used
Python
Pandas
Matplotlib
Scikit-learn
Jupyter Notebook / Google Colab
Excel dataset
📊 Project Steps
Load the sales dataset.
Check for missing values.
Clean the dataset by removing:
Missing Customer IDs
Cancelled invoices
Invalid quantities and prices
Duplicate records
Calculate the total amount for each transaction.
Create RFM values for each customer.
Standardize the RFM values using StandardScaler.
Use the Elbow Method to select the number of clusters.
Apply K-Means Clustering.
Calculate the Silhouette Score.
Calculate the Davies-Bouldin Index.
Visualize the customer clusters.
Display the average RFM values for each cluster.
📁 Dataset

The project uses a sales dataset containing transaction information such as:

Invoice
Invoice Date
Customer ID
Quantity
Price
📈 Machine Learning Algorithm
K-Means Clustering

K-Means is an unsupervised machine learning algorithm used to divide data into groups called clusters.

In this project, the algorithm groups customers based on their Recency, Frequency, and Monetary values.

📏 Evaluation Metrics

Two clustering evaluation metrics are used:

Silhouette Score

The Silhouette Score is used to measure how well the customers are separated into clusters.

Davies-Bouldin Index

The Davies-Bouldin Index measures the similarity between different clusters. A lower value generally indicates better-separated clusters.

📌 Result

The project successfully groups customers based on their purchasing behavior using RFM analysis and K-Means clustering.

The resulting clusters can help understand different types of customers and their purchasing patterns.

🚀 How to Run
Open the notebook in Jupyter Notebook or Google Colab.
Upload the sales2.xlsx dataset.
Run the notebook cells in order.
View the clustering results and graphs.
👨‍💻 Author

P Ayyanar Kanna 

BCA Student
