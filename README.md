# 🏦 Customer Churn Prediction using Artificial Neural Networks (ANN)

A Machine Learning web application that predicts whether a customer is likely to leave a bank using an Artificial Neural Network (ANN). The application is built with TensorFlow, Streamlit, and Scikit-learn, allowing users to enter customer information and receive real-time churn predictions.

## 🌐 Live Demo

🚀 **Try the application here:**

https://chern-prediction-by-omkar-patil.streamlit.app/

---

## 📌 Features

- Predicts customer churn in real time.
- Interactive Streamlit web interface.
- ANN model built using TensorFlow/Keras.
- Data preprocessing using Scikit-learn.
- Automatic feature scaling and encoding.
- Probability score for customer churn.

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Streamlit
- Matplotlib

---

## 📂 Project Structure

```
Chern-Prediction/
│
├── 3app.py
├── model.h5
├── scaler.pkl
├── label_encoder_gender.pkl
├── onehot_encoder_geo.pkl
├── Churn_Modelling.csv
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/omk18p/Chern-Prediction.git
cd Chern-Prediction
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Environment

#### Windows

```bash
.venv\Scripts\activate
```

#### Linux / macOS

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run 3app.py
```

The application will start at:

```
http://localhost:8501
```

---

## 📊 Dataset

The project uses the **Churn Modelling Dataset**, containing customer information such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card Status
- Active Membership
- Estimated Salary

These features are used by the ANN model to predict whether a customer is likely to churn.

---

## 🧠 Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Label Encoding
4. One-Hot Encoding
5. Feature Scaling
6. ANN Model Training
7. Model Evaluation
8. Model Saving
9. Streamlit Deployment

---

## 📈 Model

The prediction model is built using an Artificial Neural Network (ANN) implemented with TensorFlow/Keras.

The trained model is stored as:

```
model.h5
```

Supporting preprocessing files:

- `scaler.pkl`
- `label_encoder_gender.pkl`
- `onehot_encoder_geo.pkl`

---

## 🚀 Deployment

The application is deployed using **Streamlit Community Cloud**.

**Live Application**

https://chern-prediction-by-omkar-patil.streamlit.app/

---

## 👨‍💻 Author

**Omkar Patil**

GitHub: https://github.com/omk18p

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
