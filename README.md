Customer Segmentation on Online Retail Dataset
Project Overview

This project performs customer segmentation using the Online Retail dataset
. The goal is to analyze customer purchasing behavior and group similar customers together for targeted marketing strategies.

 Dataset

File: Online-Retail_4_.xlsx

Description: Transactions from an online retail store, including:

InvoiceNo: Unique identifier for transactions

StockCode: Product code

Description: Product description

Quantity: Quantity purchased

InvoiceDate: Date of purchase

UnitPrice: Price per unit

CustomerID: Unique customer identifier

Country: Customer’s country

 Objectives

Clean and preprocess the dataset (handle missing values, duplicates, and outliers).

Engineer features such as RFM (Recency, Frequency, Monetary) metrics.

Apply clustering algorithms:

K-Means Clustering

Hierarchical Clustering

Visualize clusters to understand customer groups and their purchasing patterns.

Provide actionable insights for targeted marketing campaigns.

 Tech Stack

Programming Language: Python

Libraries:

pandas, numpy – Data manipulation and preprocessing

matplotlib, seaborn – Data visualization

scikit-learn – Clustering algorithms

scipy – Hierarchical clustering

 Installation and Usage
1. Clone the Repository
git clone https://github.com/HARSHIT071004/Online-Retail_Clustering.git
cd Online-Retail_Clustering

2. Install Dependencies
pip install -r requirements.txt

3. Run the Notebook or Script
jupyter notebook Online_Retail_Clustering.ipynb


or

python main.py

 Results

Segmented customers into distinct groups based on their RFM scores.

Identified high-value customers and potential churners.

Provided insights for personalized marketing strategies.

 Future Improvements

Experiment with DBSCAN or Gaussian Mixture Models for clustering.

Integrate Power BI or Tableau dashboards for interactive visualizations.

Automate data pipeline for continuous updates.

 Author
Harshit Sharma
GitHub

Email: harshsharmavatasa@gmail.com
