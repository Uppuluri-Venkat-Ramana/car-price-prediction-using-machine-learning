# 🚗 Car Price Prediction using Machine Learning  

## 📌 Project Overview  
This project predicts the **selling price of cars** based on features like year, mileage, fuel type, and transmission.  
It demonstrates a complete **machine learning workflow**: data analysis, preprocessing, model building, evaluation, and deployment using Flask.  

---

## 🎯 Objectives  
- Analyze how car features affect resale prices.  
- Build regression models for price prediction.  
- Deploy a user-friendly web app for predictions.  

---

## 📂 Project Structure  
car-price-prediction-using-machine-learning/

│── Datasciene pr1/

│ ├── app.py # Flask app

│ ├── car_price_model.pkl # Trained ML model

│ ├── templates/

│ │ └── index.html # Web UI

│ └── static/ # CSS, JS (if any)

│

│── Car Price Prediction.ipynb # Jupyter Notebook

│── car data.csv # Dataset

│── README.md # Documentation

---

## 📊 Dataset  
- **Source**: Kaggle Car Dataset *(or mention actual source)*  
- **Features**: Car Name, Year, Present Price, Kms Driven, Fuel Type, Seller Type, Transmission, Owner  

---

## ⚙️ Tech Stack  
- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Flask  
- **Tools**: Jupyter Notebook, GitHub  

---

## 🔍 Workflow  
1. **EDA**: Correlation analysis, visualizations, feature importance  
2. **Preprocessing**: Encoding categorical features, scaling, train-test split  
3. **Modeling**:  
   - Linear Regression  
   - Decision Tree  
   - Random Forest (best performing, R² ≈ 0.95)  
4. **Deployment**: Flask app with form inputs & price prediction output  

---

## 🚀 Run Locally  
--- 
# Open Anaconda Prompt and activate your environment
conda activate myenv   
# replace myenv with your environment nam

# Install dependencies
pip install -r requirements.txt

# Run app
python app.py



📈 Results & Insights

 -Car price decreases with age & kilometers driven.

 -Fuel type and transmission impact resale value significantly.

 -Random Forest provided the best accuracy among models tested.

 

🔮 Future Enhancements

 -Add more ML models (XGBoost, Gradient Boosting).

 -Deploy on Streamlit/Heroku for live demo.

 -Train with larger, real-world datasets for better accuracy.

 

 ##  About the Author

**Uppuluri Venkata Ramana** — Data Enthusiast certified in BI & Marketing Analytics.  
Skilled in Python, R, SQL, Excel, and Power BI, with a passion for analyzing, visualizing, and deriving insights from data.

- **LinkedIn**: [View Profile](https://www.linkedin.com/in/uppuluri-venkata-ramana-467979214)  
- **GitHub**: [@Uppuluri-Venkata-Ramana](https://github.com/Uppuluri-Venkat-Ramana)
