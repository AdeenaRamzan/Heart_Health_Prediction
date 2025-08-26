# Heart_Health_Prediction-
Heart health prediction app powered by Machine Learning (KNN) and Streamlit.
Machine Learning-based Cardiac Risk Evaluation

This project is a Streamlit web app that predicts the likelihood of heart disease based on medical attributes such as age, cholesterol, blood pressure, ECG results, chest pain type, and more.

⚠️ Disclaimer: This tool is for educational purposes only and is not a substitute for medical advice.

🚀 Features

- Simple and interactive web interface built with Streamlit
- Predicts heart disease risk using a trained K-Nearest Neighbors (KNN) model
- Data preprocessing with scikit-learn StandardScaler
- Handles categorical inputs with one-hot encoding
- Provides clear risk output (High / Low)

📂 Project Structure
├── KNN_heart.pkl       # Trained KNN model  
├── scaler.pkl          # Scaler used for feature normalization  
├── columns.pkl         # Expected feature columns after preprocessing  
├── app.py              # Streamlit app  
├── requirements.txt    # Dependencies
├── heart_disease.ipynb # Jupyter Notebook for data analysis & model training   
└── README.md           # Project documentation  


🛠️ Installation & Setup

* Clone the repository
- git clone https://github.com/your-username/heart-health-prediction.git
cd heart-health-prediction

* Install dependencies
- pip install -r requirements.txt

* Run the app
- streamlit run app.py


📊 Input Features
- Age
- Sex (M/F)
- Chest Pain Type (ATA, NAP, TA, ASY)
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar > 120 mg/dL
- Resting ECG (Normal, ST, LVH)
- Max Heart Rate
- Exercise Induced Angina (Y/N)
- Oldpeak (ST Depression)
- ST Slope (Up, Flat, Down)


📖 Walkthrough
- Run streamlit run app.py
- Enter patient details (age, cholesterol, etc.)
- Click Predict
- Get either:
⚠️ High Risk of Heart Disease
✅ Low Risk of Heart Disease


🔮 Future Improvements
- Show probability/confidence score instead of only high/low
- Deploy app on Streamlit Cloud or Render
- Extend project with stroke prediction dataset

