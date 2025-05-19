# 🕵️‍♂️ CrimeCast – Crime Category Prediction with Ensemble Machine Learning

This project was developed as part of a Kaggle competition to predict crime categories based on time, location, and victim details. The focus was on building an accurate, generalizable ML pipeline with extensive feature engineering and ensemble models.

## 🚀 Project Highlights
- Achieved **95% accuracy** with advanced ensemble techniques.
- Balanced highly imbalanced dataset using **SMOTE**.
- Feature selection and dimensionality reduction using **SelectKBest**.
- Tuned hyperparameters using **GridSearchCV**.
- Combined predictions using **Soft Voting Ensemble** (XGBoost + LightGBM).

## 🛠️ Tech Stack
- **Python**
- **pandas**, **numpy**, **matplotlib**, **seaborn**
- **scikit-learn**
- **XGBoost**
- **LightGBM**
- **imblearn** (SMOTE)

## 📊 Machine Learning Pipeline
1. Data Cleaning and EDA
2. Feature Engineering (Label Encoding, Date-Time Extraction)
3. Class Imbalance Handling with SMOTE
4. Feature Selection with SelectKBest
5. Model Training:
    - XGBoostClassifier
    - LightGBMClassifier
    - VotingClassifier (soft voting)
6. Evaluation:
    - Accuracy: 95%
    - F1-Score and Classification Report

## 📁 Files Included
- `notebook.ipynb` – Full Kaggle notebook with code and outputs
- `requirements.txt` – List of dependencies for reproducibility

## 🔗 Original Kaggle Notebook
[Click to View on Kaggle](https://www.kaggle.com/code/ompodey/21f2000968-notebook-t22024)

## 📌 Future Work
- Deploy as an API using Flask or FastAPI
- Containerize using Docker
- Add automated retraining on new data

## 👨‍💻 Author
[Om Podey](https://www.linkedin.com/in/om-podey-0b49a9210) | [GitHub](https://github.com/ompodey)
