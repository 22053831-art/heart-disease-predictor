
# Heart Disease Predictor

A machine learning-based web application to predict the likelihood of heart disease based on patient medical data.  
This project uses a *Logistic Regression model* trained on the heart_disease_data.csv dataset and is deployed with *Gradio* for an interactive UI.

---

## 📌 Features
- Predicts if a patient has heart disease or not.
- Simple web interface built with *Gradio*.
- Model trained using *scikit-learn* Logistic Regression.
- Supports input for common heart disease risk factors.

---

## 📂 Project Structure
├── app.py # Gradio web app for predictions
├── finalheartdiseasepredictor.py # Model training script
├── heart_disease_data.csv # Dataset
├── HeartDiseasePredictor.pkl # Trained model file
└── README.md # Project documentation

---


## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/heart-disease-predictor.git
cd heart-disease-predictor

pip install -r requirements.txt
gradio
pandas
numpy
scikit-learn
joblib

python finalheartdiseasepredictor.py
python app.py
