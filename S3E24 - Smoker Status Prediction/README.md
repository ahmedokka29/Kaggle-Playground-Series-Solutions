# Smoker Status Prediction (Bio-Signals)

Predict smoking status using physiological features like BMI, blood pressure, and cholesterol levels.  

## 🚀 Results

- **ROC AUC**: 0.874  
- **Accuracy**: 79%  
- **Key Features**: BMI, systolic blood pressure, hemoglobin.  

## 🛠️ Technologies

- **Model**: XGBoost  
- **Tools**: Pandas, Scikit-learn, Matplotlib  
- **Techniques**: Calculate BMI and add it as a new column in the DataFrame  

## 📊 EDA Highlights

- Class imbalance: 65% non-smokers vs 35% smokers.

<p align="center">
<img src="./Smoker vs Non-Smoker Distribution.png" alt="Smoker vs Non-Smoker Distribution">
</p>

- Strong correlation between `systolic` and `hemoglobin`.  
