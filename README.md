# Heart Disease Prediction Using Machine Learning

## Project Overview

Heart Disease Prediction is a Machine Learning-based web application that predicts the possibility of heart disease based on patient health parameters.

The project uses a trained Support Vector Machine (SVM) classification model and an interactive Streamlit interface that allows users to enter medical attributes and receive predictions.

## Objectives

- Predict the possibility of heart disease using Machine Learning.
- Perform data preprocessing and feature engineering.
- Train and evaluate a classification model.
- Develop an interactive web interface using Streamlit.
- Provide real-time predictions based on user inputs.

## Technologies Used

- **Programming Language:** Python
- **Machine Learning:** Scikit-learn
- **Algorithm:** Support Vector Machine (SVM)
- **Data Processing:** Pandas, NumPy
- **Web Framework:** Streamlit
- **Model Serialization:** Pickle
- **Development Tools:** Google Colab, VS Code

## Project Workflow

1. Dataset Collection
2. Data Preprocessing
3. Feature Selection and Encoding
4. Feature Scaling
5. Model Training using SVM
6. Model Evaluation
7. Saving the trained model and preprocessing objects
8. Integration with Streamlit
9. Making predictions through the web interface

## Project Structure


Heart-Disease-Prediction/
│
├── app.py
├── models/
│   ├── SVM_Heart.pkl
│   ├── scaler.pkl
│   └── columns.pkl
│
├── dataset/
│   └── heart.csv
│
├── requirements.txt
├── README.md
└── .gitignore




## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Siddham-coder/heart_disease_prediction.git
```

### 2. Navigate to the Project Directory

```bash
cd heart_disease_prediction
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Streamlit Application

```bash
streamlit run app.py
```

The application will open in your browser.

## 🧠 Machine Learning Model

The project uses a Support Vector Machine (SVM) classifier to perform binary classification.

The trained model, scaler, and feature-column information are saved and reused in the Streamlit application for consistent preprocessing and prediction.

## 📊 Model Evaluation

The model is evaluated using appropriate classification metrics, such as:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## ⚠️ Disclaimer

This application is developed for educational and academic purposes only. It is not intended to replace professional medical diagnosis, advice, or treatment.

## 👨‍💻 Author

**Siddham Vispute**

GitHub: [@Siddham-coder](https://github.com/Siddham-coder)
