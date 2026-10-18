# SmartCart — Customer Segmentation Using Machine Learning

## Overview
SmartCart is a customer segmentation project that analyzes customer demographics, income, and spending behavior to identify groups of customers with similar characteristics.

## Objectives
- Clean and preprocess customer data.
- Engineer features such as age, customer tenure, and total spending.
- Explore relationships between customer attributes.
- Apply dimensionality reduction using PCA.
- Determine suitable cluster counts using the Elbow Method and Silhouette Score.
- Compare K-Means and Agglomerative Clustering.
- Analyze customer segments using cluster summaries and visualizations.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Kneed

## Algorithms
- Principal Component Analysis (PCA)
- K-Means Clustering
- Agglomerative Clustering

## Project Structure
```text
SmartCart/
├── smartcart.ipynb
├── smartcart_customers.csv
├── README.md
├── requirements.txt
└── .gitignore
```

## Getting Started
1. Clone or download the repository.
2. Install the required Python libraries.
3. Place `smartcart_customers.csv` in the same directory as the notebook.
4. Open `smartcart.ipynb` in Jupyter Notebook.
5. Run the notebook cells in order.

## Installation
```bash
pip install -r requirements.txt
```

## Expected Outcome
The analysis groups customers into segments based on their characteristics and spending patterns, helping explore customer behavior and potential marketing strategies.

## Disclaimer
This project is intended for educational and analytical purposes. Cluster assignments are exploratory and should be validated before business use.
