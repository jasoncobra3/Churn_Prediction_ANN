# 🔮 Customer Churn Prediction with ANN

This project is an AI-powered customer churn prediction system built with TensorFlow/Keras and deployed via Streamlit. It predicts whether a bank customer is likely to leave (churn) based on key demographic, financial, and behavioral features.

With an intuitive UI, users can input customer details and instantly see the churn probability along with a clear prediction.

---

## 🚀 Features

- 🧠 Deep Learning Model – Artificial Neural Network (ANN) trained on customer data
- ⚙️ Preprocessing Pipelines – Includes Label Encoding, One-Hot Encoding, and Feature Scaling
- 🌍 Geography & Gender Handling – Encoded with pre-trained label & one-hot encoders
- 📊 Interactive Streamlit App – User-friendly input fields for real-time churn prediction
- 🔮 Probability Output – Shows exact churn likelihood with clear interpretation

---

## 🧰 Tech Stack

- Python 🐍
- TensorFlow / Keras – Deep learning model
- Scikit-learn – Preprocessing (scalers, encoders)
- Pandas, NumPy – Data handling
- Streamlit – Frontend web app
- Pickle – Saving/loading encoders and scaler

--- 

## 📦 Installation

1. **Clone the Repo**
   ```bash
   git clone https://github.com/jasoncobra3/Churn_Prediction_ANN.git
   cd Churn_Prediction_ANN

2. **Create Virtual Environment & Install Dependencies**
   ```bash
    python -m venv venv
    source venv/bin/activate   # macOS/Linux
    venv\Scripts\activate      # Windows
    pip install -r requirements.txt

3. **Ensure Model & Encoders Exist**
   - `model.h5` (Trained ANN model)
   - `label_encoder_gender.pkl`
   - `onehot_encoder_geo.pkl`
   - `scaler.pkl`
  
---

## 📁 Project Structure
```
├── app.py                   # Streamlit app
├── model.h5                 # Trained ANN model
├── label_encoder_gender.pkl  # Saved LabelEncoder for Gender
├── onehot_encoder_geo.pkl    # Saved OneHotEncoder for Geography
├── scaler.pkl                # Saved StandardScaler
├── requirements.txt          # Dependencies
└── README.md                 # Project documentation
```

## 🤝 Contributing

Pull requests are welcome! If you’d like to add new features (e.g., model retraining, SHAP explanations), feel free to fork and improve 🚀
