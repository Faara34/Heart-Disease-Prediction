
# Heart Disease Prediction

Predicts whether a patient has heart disease using machine learning.

**Inputs (Features):**  
Age, Sex, Chest pain type, Blood pressure, Cholesterol, Fasting blood sugar, ECG results, Max heart rate, Exercise-induced angina, ST depression, ST slope, Major vessels, Thalassemia  

**Output (Target):**  
- `Heart Disease` (0 = Absence, 1 = Presence)  
- Probability score for each patient  

**Models Used:**  
- Logistic Regression  
- Random Forest  
- XGBoost  

**Usage:**  
After training, the model outputs a CSV with `id` and `Heart Disease` probability for each patient.  

Libraries used:
pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn  

