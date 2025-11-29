# 🏡 Bengaluru House Price Prediction – Machine Learning Project

This project predicts house prices in Bengaluru using Machine Learning techniques. The dataset includes key housing features such as location, total square feet, number of bathrooms, and BHK. The model is built using a complete end-to-end pipeline including data cleaning, preprocessing, feature engineering, model training, and evaluation.

---

## 📌 Features of the Project
- Cleaned and processed real-world Bengaluru housing dataset  
- Converted text-based fields like *size* into numerical BHK  
- Handled total_sqft ranges and missing values  
- Performed One-Hot Encoding and feature scaling  
- Used **Random Forest Regressor** for accurate predictions  
- Evaluated performance using **RMSE** and **MAE**  
- Includes example prediction for new input data  

---

## 📂 Project Structure
Bengaluru-House-Price-Prediction/
│
├── data/
│ └── Bengaluru_House_Data.csv
│
├── notebooks/
│ └── house_price_prediction.ipynb # Google Colab notebook
│
├── src/
│ ├── preprocessing.py # Data cleaning & feature engineering
│ ├── model.py # Model training code
│ └── prediction_example.py # Sample prediction script
│
├── models/
│ └── house_price_model.pkl # Saved trained model
│
├── README.md
└── requirements.txt

---

## 🚀 Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  
- Seaborn  

---

## 📊 Model Overview
The **RandomForestRegressor** was chosen due to its strong performance on tabular datasets and robustness to noisy or non-linear features.

### **Metrics**
- RMSE  
- MAE  

These metrics help evaluate how close the predicted prices are to actual market values.

---

## 🧪 Example Prediction
```python
sample = {
    'location': 'Whitefield',
    'total_sqft': 1200,
    'bath': 2,
    'bhk': 2
}
The model outputs the expected house price (in lakh INR).

📈 Future Improvements

Add more ML models (XGBoost, LightGBM)

Build a Streamlit/Gradio web app

Hyperparameter tuning for improved accuracy

🤝 Contributing

Pull requests and improvements are welcome. Please create an issue first to discuss major changes.


