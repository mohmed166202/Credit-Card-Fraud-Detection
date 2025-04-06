# 📄 README.md

# Credit Card Fraud Detection 🕵️‍♂️💳

This project focuses on detecting fraudulent credit card transactions using machine learning. It uses a real-world anonymized dataset and applies classification techniques to identify suspicious activity.

## 📁 Files

- `Credit Card Fraud Detection.ipynb`: Contains all steps including data preprocessing, model training, and evaluation.

## 📊 Dataset

- **Download Link**: [Google Drive Dataset](https://drive.google.com/file/d/1e_4d3Yck7ZNz6clXU6BCyiUYMFZ0hm65/view?usp=sharing)
- **Description**:
  - Total transactions: 284,807
  - Fraudulent transactions: 492 (0.172%)
  - Features are anonymized via PCA, except for `Time` and `Amount`

## 🧠 Models Used

- Logistic Regression
- Random Forest
- XGBoost

## 📈 Evaluation Metrics

- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Curve

## ⚙️ Installation

To run this project locally:

```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt
```

Or manually install:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

## 🚀 Future Improvements

- Use SMOTE or ADASYN for better handling of class imbalance
- Integrate deep learning methods like LSTM
- Use SHAP for model explainability

## 📬 Contact

Feel free to reach out: your-email@example.com


# 📄 requirements.txt

pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost


# 📄 .gitignore

__pycache__/
.ipynb_checkpoints/
.env
.DS_Store
*.pyc
*.pyo
*.pyd
*.sqlite3
*.h5
*.log
