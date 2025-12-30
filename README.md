# Phone-Price-Prediction

Phone Price Prediction (ML Project)

Predict mobile phone prices based on specifications using Machine Learning.

🚀 Project Summary

Built regression models to estimate phone prices

Compared Linear Regression vs Random Forest

Random Forest performed best

Saved model for reuse (.pkl file)

📂 Files
Phone-Price-Prediction
│
├── data
│   └── mobile_phone_price.csv
│
├── models
│   └── random_forest_phone_price_model.pkl
│
├── notebooks
│   └── Phone_Price_Prediction.ipynb
│
├── scripts
│   └── phone_price_prediction.py
│
├── requirements.txt
└── README.md

🧾 Dataset

Mobile phone price dataset containing:

Brand

RAM

Storage

Screen Size

Camera

Battery Capacity

Price

🧹 Pre-processing

Cleaned price values

Removed extra spaces

Converted RAM & Storage to numbers

Extracted numeric screen size & camera values

One-hot encoded Brand

📊 Model Performance

Metrics:

Mean Absolute Error (MAE)

R² Score

👉 Random Forest selected as final model

Model saved as:

random_forest_phone_price_model.pkl

▶️ How to Run
Install dependencies
pip install -r requirements.txt

Open notebook
notebooks/Phone_Price_Prediction.ipynb

Or run script
python scripts/phone_price_prediction.py

🎯 Skills Demonstrated

Data cleaning & preprocessing

Feature engineering

Model training & evaluation

Saving ML models (joblib)
