
# 💳 Smart Loan Risk Prediction System

An end-to-end Machine Learning project that predicts whether a loan application will be **Approved** or **Rejected** based on an applicant's financial profile. The project also demonstrates data preprocessing, exploratory data analysis (EDA), regression, classification, model evaluation, cross-validation, and deployment using Streamlit.

---

## 📌 Project Overview

Financial institutions receive thousands of loan applications every day. Evaluating each application manually is time-consuming and may introduce inconsistencies.

This project uses Machine Learning algorithms to analyze applicant information and predict loan approval, helping automate and improve the loan screening process.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Build Regression and Classification models
- Compare multiple Machine Learning algorithms
- Evaluate models using various performance metrics
- Perform Cross Validation
- Save the best trained model
- Deploy the model using Streamlit

---

## 📂 Project Structure

```
Loan-Risk-Prediction-System/
│
├── data/
│      loan_approval_dataset.csv
│
├── notebooks/
│      01_EDA.ipynb
│      02_Data_Preprocessing.ipynb
│      03_Regression_Model.ipynb
│      04_Classification_Model.ipynb
│      05_Model_Comparison.ipynb
│
├── models/
│      regression_model.pkl
│      classification_model.pkl
│
├── streamlit_app/
│      app.py
│
├── images/
│
├── README.md
├── requirements.txt
└── presentation.pptx
```

---

# 📊 Dataset

The dataset contains information about loan applicants including:

| Feature | Description |
|----------|-------------|
| Loan ID | Unique Loan Identifier |
| Number of Dependents | Applicant's dependents |
| Education | Graduate / Not Graduate |
| Self Employed | Employment Status |
| Annual Income | Applicant Annual Income |
| Loan Amount | Requested Loan Amount |
| Loan Term | Loan Duration |
| CIBIL Score | Credit Score |
| Residential Assets | Residential Property Value |
| Commercial Assets | Commercial Property Value |
| Luxury Assets | Luxury Assets Value |
| Bank Assets | Bank Balance |
| Loan Status | Approved / Rejected |

---

# 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Joblib
- Streamlit
- Git
- GitHub

---

# 📈 Exploratory Data Analysis

The following analyses were performed:

- Dataset Overview
- Missing Value Analysis
- Duplicate Record Detection
- Data Type Inspection
- Statistical Summary
- Correlation Analysis
- Feature Distribution
- Class Distribution
- Outlier Detection
- Feature Relationships

### Visualizations

- Histograms
- Bar Charts
- Box Plots
- Scatter Plots
- Correlation Heatmap
- Count Plots

---

# ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Removing extra spaces
- Handling missing values
- Duplicate removal
- Label Encoding
- Feature Scaling
- Train-Test Split

---

# 🤖 Machine Learning Models

## Regression Models

- Simple Linear Regression
- Multiple Linear Regression

Regression Metrics

- MAE
- MSE
- RMSE
- R² Score

---

## Classification Models

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

Classification Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Score

---

# 🔄 Cross Validation

The project uses:

- K-Fold Cross Validation
- Stratified K-Fold Cross Validation

This helps evaluate the model on multiple train-test splits for more reliable performance.

---

# 🔍 Hyperparameter Tuning

GridSearchCV is used to optimize:

- KNN Parameters
- SVM Parameters
- Logistic Regression Parameters

---

# 🏆 Model Comparison

The performance of all algorithms is compared using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

The best-performing model is selected for deployment.

---

# 💻 Streamlit Application

The Streamlit application allows users to enter applicant information and predicts:

- Loan Approval Status
- Prediction Probability

---

# 📁 Model Saving

The trained models are saved using Joblib.

Example:

```python
import joblib

joblib.dump(model, "classification_model.pkl")
```

---

# ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/YourUsername/Smart-Loan-Risk-Prediction-System.git
```

Navigate to the project:

```bash
cd Smart-Loan-Risk-Prediction-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# 🚀 Run Streamlit App

```bash
streamlit run streamlit_app/app.py
```

---

# 📊 Results

The project compares multiple Machine Learning models and selects the best-performing model based on evaluation metrics.

---

# 📷 Project Screenshots

Add screenshots here after completing the project.

Example:

- Dataset Overview
- Correlation Heatmap
- Confusion Matrix
- ROC Curve
- Streamlit Interface

---

# 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Regression
- Classification
- Cross Validation
- Hyperparameter Tuning
- Model Evaluation
- Model Deployment
- Git & GitHub

---

# 🔮 Future Improvements

- Random Forest
- XGBoost
- LightGBM
- SHAP Explainability
- LIME
- Flask/FastAPI API Deployment
- Docker Containerization
- Cloud Deployment (AWS/Azure/GCP)

---

# 👨‍💻 Author

**Sunil Tripathi**

B.Tech CSE (Data Science)

Python | SQL | Power BI | Machine Learning | Data Analytics

---

## ⭐ If you found this project helpful, consider giving it a Star!
