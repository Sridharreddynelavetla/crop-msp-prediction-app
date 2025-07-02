# crop-msp-prediction-app
An AI-powered Crop Minimum Support Price (MSP) Prediction Web App using XGBoost and Streamlit, with SMS alert and OTP verification via Twilio.

🌾 Crop MSP Prediction Web App
This project predicts the Minimum Support Price (MSP) of agricultural crops based on historical data using machine learning (XGBoost). It includes a user-friendly Streamlit interface and SMS notifications (with OTP verification) for farmers using Twilio.

Features:-
1.Crop MSP prediction using XGBoost Regressor
2.Intuitive UI built with Streamlit
3.OTP-based phone verification using Twilio Verify API
4.SMS alerts to farmers with predicted MSP

Technologies Used:-
1.Python
2.Pandas, NumPy, Matplotlib, Seaborn
3.XGBoost, scikit-learn
4.Streamlit
5.Twilio SMS & OTP verification API

Model Training:-
Model trained using:
    1.GridSearchCV for hyperparameter tuning
    2.R² Score for accuracy evaluation
    3.Actual vs Predicted MSP visualization
Files:-
1.crop_price.xlsx – Dataset
2.xgb_crop_model1.pkl – Trained model
3.crop_app.py – Streamlit app with Twilio integration
4.best_xgb_params.xlsx – Best parameters from GridSearchCV
5.msp_predictions1.xlsx – Actual vs predicted values

How to Run
Clone the repo:

git clone https://github.com/your-username/crop-msp-prediction-app.git
cd crop-msp-prediction-app

How to Run in Web Site:-
    streamlit run crop_app.py

Twilio Setup:-
1.Set your Twilio credentials and Verify SID in the script.
2.Use send_otp() to send OTP and check_otp() to verify.
3.After verification, the user receives the predicted MSP via SMS.
