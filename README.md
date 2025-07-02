House Price Prediction System 🏠💰
📌 Overview
This project is a machine learning-based system designed to predict house prices based on various features such as area, number of bedrooms, bathrooms, location amenities, and more. The system uses regression algorithms to analyze historical housing data and provide accurate price predictions for residential properties.

📊 Dataset
The dataset contains information about 545 residential properties, with the following key features:

Numerical Features:

area (in square feet)

bedrooms, bathrooms, stories, parking spaces

Categorical Features:

mainroad (access to main road: yes/no)

guestroom, basement, hotwaterheating, airconditioning

prefarea (preferred location: yes/no)

furnishingstatus (furnished/semi-furnished/unfurnished)

Target Variable:

price (in ₹)

🔧 Features
✅ Data Preprocessing

Handles missing values (if any)

Scales numerical features

Encodes categorical variables

✅ Multiple ML Models

Linear Regression

Ridge & Lasso Regression

Random Forest

Gradient Boosting

✅ Model Evaluation

Metrics: MAE, MSE, RMSE, R²

Cross-validation for robustness

✅ Feature Importance Analysis

Identifies key factors influencing house prices

✅ Prediction Function

Takes user inputs & predicts price

✅ Deployment-Ready

Save & load trained models

Optional Streamlit web app for easy use

🚀 How It Works
Data Preparation:

Load and clean the dataset

Split into training & testing sets

Model Training:

Train multiple regression models

Optimize hyperparameters

Prediction:

Input property features

Get predicted price

📈 Results
Model MAE (₹) RMSE (₹) R² Score
Random Forest ~1,000,000 ~1,500,000 ~0.85
Gradient Boosting ~1,100,000 ~1,600,000 ~0.83
Linear Regression ~1,300,000 ~1,800,000 ~0.78
(Example metrics - replace with your actual results)

🛠️ Installation
Clone the repository:

bash
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
Install dependencies:

bash
pip install -r requirements.txt
Run the Jupyter notebook:

bash
jupyter notebook House_Price_Prediction.ipynb
(Optional) Launch the Streamlit app:

bash
streamlit run app.py
📂 File Structure
text
house-price-prediction/
├── data/
│ └── Housing.csv # Dataset
├── models/
│ └── house_price_predictor.pkl # Saved model
├── House_Price_Prediction.ipynb # Jupyter notebook
├── app.py # Streamlit app (optional)
├── README.md
└── requirements.txt # Dependencies
🤖 Technologies Used
Python (Primary language)

Pandas & NumPy (Data manipulation)

Scikit-learn (ML algorithms)

Matplotlib & Seaborn (Visualization)

Streamlit (Web app - optional)
