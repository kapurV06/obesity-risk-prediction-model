# Obesity Risk Prediction Model

This project predicts the obesity risk category of a user based on lifestyle, dietary habits, and physical parameters. It includes a machine learning model, a Flask backend, and a responsive frontend UI.

## Tech Stack

- **Frontend**: HTML, CSS (Nord theme with Tailwind), JavaScript
- **Backend**: Flask, Python, scikit-learn
- **Model**: Trained using ensemble learning with preprocessing pipeline
- **Deployment**:
  - Frontend: Vercel
  - Backend: Railway

## Live URLs

- **Frontend**: [Link to UI](https://obesity-risk-prediction-model.vercel.app/)
- **Backend API**: [Railway](https://obesity-risk-prediction-model-backend1-production.up.railway.app/)

## 📂 Project Structure

obesity-risk-prediction/
├── models/ # Serialized model, scalers, encoders
├── UI/ # Frontend HTML, CSS, JS files
├── app.py # Flask backend
├── requirements.txt # Python dependencies
└── README.md # You're here

## 🚀 How to Run Locally

1. Clone this repo:
   git clone https://github.com/kapurV06/obesity-risk-prediction-model.git
   cd obesity-risk-prediction-model
2. Set up a virtual environment and install dependencies:
   pip install -r requirements.txt
3. Run the Flask app:
   python app.py
   Open UI/index.html in your browser.
