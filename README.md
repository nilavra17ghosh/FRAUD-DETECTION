# Credit Card Fraud Detection

This project analyzes and predicts fraudulent credit card transactions using machine learning models. The dataset is highly imbalanced, making it a real-world challenge for classification algorithms.

## Features
- Data exploration and visualization
- Handling class imbalance
- Model building: Random Forest, Logistic Regression, Decision Tree
- Evaluation using accuracy, precision, recall, F1-score, and confusion matrix
- Model comparison and business insights

## Dataset
- Source: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)


## Usage
1. Clone the repository and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Jupyter notebook:
   ```bash
   jupyter notebook "Credit Card Fraud Detection.ipynb"
   ```

## Results
- All models achieve high accuracy, but recall and precision are emphasized due to class imbalance.
- Recommendations are provided for further improvements (e.g., SMOTE, ensemble methods).

