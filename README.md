# 🏥 Patient Readmission Prediction

##  Objective
The goal of this project is to build a machine learning model that predicts whether a patient will be readmitted within 30 days of discharge using synthetic hospital data. This can help hospitals reduce readmission rates and improve patient care.

---

##  Domain
**Healthcare**

---

##  Tools & Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Random Forest Classifier
- Feature Importance
- Jupyter Notebook

---

##  Dataset Information

- **Source**: Synthetic hospital dataset  
- **Records**: 30,000 patients (approx)  
- **Target Variable**: `readmitted_30_days` (Binary: 1 = Yes, 0 = No)  
- **Features**: 11+ input variables including patient_id,	age	gender,	blood_pressure,	cholesterol,	bmi	diabetes,	hypertension,	medication_count,	length_of_stay,	discharge_destination,	readmitted_30_days
---

##  Project Highlights

-  Performed Exploratory Data Analysis (EDA) to understand key readmission patterns.
-  Analyzed **50+ variables** to identify important clinical and operational features.
-  Built a **Random Forest model** to classify patients as likely to be readmitted or not.
-  Evaluated model using **accuracy, recall**, and **ROC curve**.
-  Focused on improving recall for predicting the **readmitted class (1)**.

---

##  How to Run This Project

1. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
