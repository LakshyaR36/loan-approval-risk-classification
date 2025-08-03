## 🏷️ Borrower Risk Classification using XGBoost
This project involves the development of a high-accuracy multi-class classification model that predicts borrower risk levels — labeled as p1, p2, p3, and p4 — based on structured financial and behavioral loan data. Built as part of a Machine Learning competition, the objective was to assist lenders in better credit decision-making by automatically identifying the risk group of a potential borrower.

By leveraging the power of XGBoost, one of the most powerful gradient boosting frameworks, the model achieves near-perfect predictive performance and provides an interpretable foundation for real-world financial scoring and loan approval workflows.

## 🔍 Objective

Classify borrowers into four risk levels using financial and behavioral attributes, enabling better loan approval decisions.


## 🚀 Tech Stack

- Python (Pandas, NumPy, scikit-learn, XGBoost)
- Model persistence with `pickle`
- Evaluation metrics: Accuracy, F1-Score, Confusion Matrix, Cohen's Kappa, MCC

## 📈 Results

- Accuracy: **99.38%**
- Balanced Accuracy: **98.81%**
- Cohen Kappa Score: **0.989**
- MCC: **0.989**
- Hamming Loss: **0.0061**

## 🧠 Model

- `XGBClassifier` with `multi:softmax` objective
- Train-test split: 50-50 for robust validation
- Highly interpretable confusion matrix and classification report


