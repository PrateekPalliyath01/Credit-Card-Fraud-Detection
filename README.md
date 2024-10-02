# Credit-Card-Fraud-Detection
This project aims to detect fraudulent credit card transactions using machine learning techniques.
The dataset contains transactions made by credit card holders, where each transaction is labeled as fraudulent or non-fraudulent. The goal is to build a predictive model that can accurately classify transactions as either fraudulent or legitimate.

## Dataset
The dataset used for this project is sourced from Kaggle's Credit Card Fraud Detection Dataset. It contains transactions made by European credit card holders over two days in September 2013. The dataset consists of 284,807 transactions, with 492 fraudulent transactions, representing 0.172% of the data.

## Features
The dataset includes 30 input features:
V1 to V28: Principal components obtained using PCA (due to confidentiality of the data).
Time: Number of seconds elapsed between this transaction and the first transaction in the dataset.
Amount: Transaction amount.
Class: Label for fraud detection (0: legitimate, 1: fraudulent).

Credit-Card-Fraud-Detection/
│
├── data/ 
│   └── creditcard.csv         # Dataset file
│
├── notebooks/
│   └── Fraud_Detection.ipynb  # Jupyter notebook containing the code for EDA, model training, and evaluation
│
├── src/
│   ├── data_preprocessing.py  # Data cleaning and preprocessing steps
│   ├── model_training.py      # Code for training machine learning models
│   ├── model_evaluation.py    # Evaluation metrics and visualizations
│
├── README.md                  # Project documentation
│
└── requirements.txt           # Required packages and dependencies

## Libraries and Tools Used
Python: Core programming language
pandas: Data manipulation and analysis
numpy: Mathematical operations
scikit-learn: Machine learning model implementation and evaluation
matplotlib & seaborn: Data visualization
imbalanced-learn: Handling imbalanced dataset
Jupyter Notebook: For interactive development

## Installation

1. Clone this repository:
git clone https://github.com/yourusername/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection

2. Install the required libraries:
pip install -r requirements.txt

3. Run the Jupyter Notebook:
jupyter notebook




