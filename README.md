# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Overview
This project develops machine learning models to predict the risk of heart disease using structured healthcare data.

## 🚀 Objectives
- Build classification models for disease prediction  
- Compare performance of different algorithms  
- Address overfitting and improve model generalization  

## 🧠 Models Used
- Logistic Regression  
- Random Forest  

## 📊 Results
- Logistic Regression Accuracy: ~80%  
- Random Forest Accuracy: ~98% (overfitting observed)  
- Tuned Random Forest (optimized max_depth=10): ~88% 
- Cross-validation Accuracy: ~91.9%  

## 🔍 Key Insights
- Ensemble models outperform linear models  
- Overfitting was detected and reduced using hyperparameter tuning  
- Feature importance analysis identified key predictors  

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib  

## 📁 Project Structure
heart-disease-prediction-ml/
│── heart_disease_prediction.ipynb  
│── README.md  
│── requirements.txt  

## 📌 Future Improvements
- Hyperparameter tuning (GridSearchCV)  
- Use of advanced models (XGBoost)  
- Deployment using Streamlit  
## ⚙️ Hyperparameter Tuning
- Applied GridSearchCV to optimize Random Forest model  
- Best parameter: max_depth = 10  
- Improved generalization and reduced overfitting
## Cross-validation accuracy: ~91.9%
