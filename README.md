# ❤️ Heart Disease Prediction App

A Machine Learning-powered web application built with **Streamlit** that predicts the likelihood of heart disease based on patient health parameters.

## 🚀 Features

- User-friendly Streamlit interface
- Real-time heart disease prediction
- Machine Learning model trained using KNN
- Data preprocessing using StandardScaler
- Instant prediction results

## 🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-Learn
- Joblib

## 📂 Project Structure

```
heart-disease-prediction/
│
├── app.py
├── knn_heart_model.pkl
├── heart_scaler.pkl
├── heart_columns.pkl
├── heart.xls
├── Heart.ipynb
├── requirements.txt
└── README.md
```

## 📊 Input Features

The model uses the following health parameters:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression
- Slope
- Number of Major Vessels
- Thalassemia

## ▶️ Run Locally

### Clone Repository

```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Streamlit App

```bash
streamlit run app.py
```

## 🌐 Live Demo

Deploy easily using Streamlit Community Cloud.

## 📈 Model Information

- Algorithm: K-Nearest Neighbors (KNN)
- Preprocessing: StandardScaler
- Model Storage: Joblib (.pkl)

## ⚠️ Disclaimer

This application is intended for educational and research purposes only. It should not be used as a substitute for professional medical diagnosis or advice.

## 👨‍💻 Author

**Ankush Rawat**

GitHub: https://github.com/AnkushRawat0
