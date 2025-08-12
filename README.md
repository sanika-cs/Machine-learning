# Weather-Related Disease Prediction

This project aims to predict disease prognosis based on weather conditions and patient symptoms using machine learning models. The dataset includes weather variables such as temperature, humidity, and wind speed, along with patient demographic and symptom features.

---

## Dataset

The dataset consists of the following features:

- **Demographic and Weather Data:**  
  Age, Gender, Temperature (C), Humidity, Wind Speed (km/h)

- **Symptoms and Medical History:**  
  nausea, joint_pain, abdominal_pain, high_fever, chills, fatigue, runny_nose, pain_behind_the_eyes, dizziness, headache, chest_pain, vomiting, cough, shivering, asthma_history, high_cholesterol, diabetes, obesity, hiv_aids, nasal_polyps, asthma, high_blood_pressure, severe_headache, weakness, trouble_seeing, fever, body_aches, sore_throat, sneezing, diarrhea, rapid_breathing, rapid_heart_rate, pain_behind_eyes, swollen_glands, rashes, sinus_headache, facial_pain, shortness_of_breath, reduced_smell_and_taste, skin_irritation, itchiness, throbbing_headache, confusion, back_pain, knee_ache

- **Target Variable:**  
  `prognosis` (disease diagnosis/outcome)

---

## Models Used

- Random Forest Classifier with hyperparameter tuning using GridSearchCV
- Logistic Regression
- Support Vector Machine (SVM)
- XGBoost Classifier

Random Forest was selected as the best performing model after tuning.

---

## Project Workflow

1. **Data Preprocessing:**  
   Cleaning, feature selection, and encoding of categorical variables.

2. **Model Training:**  
   Training and hyperparameter tuning of Random Forest, and training of Logistic Regression, SVM, and XGBoost models.

3. **Evaluation:**  
   Model performance compared using classification metrics such as accuracy, precision, recall, and F1-score.

4. **Deployment:**  
   The best model (Random Forest) deployed as an interactive web app using [Gradio].

