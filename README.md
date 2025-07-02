# crop-msp-prediction-app
An AI-powered Crop Minimum Support Price (MSP) Prediction Web App using XGBoost and Streamlit, with SMS alert and OTP verification via Twilio.
You can paste the following into your README.md file:

🌾 Crop MSP Prediction Web App
This project predicts the Minimum Support Price (MSP) of agricultural crops based on historical data using machine learning (XGBoost). It includes a user-friendly Streamlit interface and SMS notifications (with OTP verification) for farmers using Twilio.

🚀 Features
Crop MSP prediction using XGBoost Regressor

Intuitive UI built with Streamlit

OTP-based phone verification using Twilio Verify API

SMS alerts to farmers with predicted MSP

🛠️ Technologies Used
Python

Pandas, NumPy, Matplotlib, Seaborn

XGBoost, scikit-learn

Streamlit

Twilio SMS & OTP verification API

🧪 Model Training
Model trained using:

GridSearchCV for hyperparameter tuning

R² Score for accuracy evaluation

Actual vs Predicted MSP visualization

📦 Files
crop_price.xlsx – Dataset

xgb_crop_model1.pkl – Trained model

crop_app.py – Streamlit app with Twilio integration

best_xgb_params.xlsx – Best parameters from GridSearchCV

msp_predictions1.xlsx – Actual vs predicted values

🔧 How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/crop-msp-prediction-app.git
cd crop-msp-prediction-app
Install dependencies:

nginx
Copy
Edit
pip install -r requirements.txt
Run the app:

arduino
Copy
Edit
streamlit run crop_app.py
🔐 Twilio Setup
Set your Twilio credentials and Verify SID in the script.

Use send_otp() to send OTP and check_otp() to verify.

After verification, the user receives the predicted MSP via SMS.
