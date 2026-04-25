# 🫀 HealthWise: Fuzzy Expert System for CHD Risk Prediction

A Fuzzy Expert System designed to estimate the risk of Coronary Heart Disease (CHD) using uncertain medical data.

## 📌 Overview
HealthWise is an intelligent system that uses Fuzzy Logic to simulate human medical reasoning. Instead of relying on rigid thresholds, it works with linguistic values such as Low, Medium, and High to provide interpretable risk predictions.

## 🎯 Objective
To develop a decision-support system that predicts CHD risk based on key medical indicators:
- Blood Pressure
- Cholesterol Level
- Heart Rate

## 🧠 Methodology
The system follows the Mamdani Fuzzy Inference approach:
1. Fuzzification
2. Rule Evaluation
3. Aggregation
4. Defuzzification (Centroid Method)

## ⚙️ Technologies Used
- Python
- scikit-fuzzy
- NumPy
- Matplotlib

## 📊 Input Variables
- Blood Pressure: Low, Medium, High
- Cholesterol: Low, High
- Heart Rate: Slow, Moderate, Fast

## 🧾 Fuzzy Rule Base
Example rule:
IF Blood Pressure is High AND Cholesterol is High AND Heart Rate is Fast THEN CHD Risk is Sick

The system includes 6 expert-defined rules based on medical reasoning.

## 📈 Results
Patient 1 → BP: 105, Chol: 160, HR: 55 → CHD: 0.61 → Healthy  
Patient 2 → BP: 120, Chol: 195, HR: 65 → CHD: 0.73 → Healthy  
Patient 3 → BP: 165, Chol: 186, HR: 95 → CHD: 2.63 → Higher Risk  

Manual calculations closely match system outputs.

## 📉 Interpretation
0 – 1.5 → Healthy  
1.3 – 2.7 → Middle Risk  
2.5 – 4 → Sick  

## ⚠️ Limitations
- Uses only 3 medical features
- Limited rule base
- Some inputs may not activate any rule

## 🚀 Future Work
- Add more features (BMI, age, smoking)
- Use real medical datasets
- Expand rule base
- Build a graphical user interface


## 👩‍💻 Author
Asala Abu Ghararah  
Data Science & Artificial Intelligence Student

## 🔗 Links
GitHub Profile: https://github.com/asala-ai  

## 💬 Feedback
Feel free to share your thoughts or suggestions!
