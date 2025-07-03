Disease Prediction Using Machine Learning (Heart Disease Detection)
This project uses machine learning techniques to predict the presence of heart disease based on patient clinical data. The goal is to assist in early diagnosis and improve medical decision-making.

The dataset used is heart_disease_dataset.csv,
which includes patient data such as:
Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol
Fasting Blood Sugar
Max Heart Rate
Exercise-Induced Angina
ST Depression
Number of major vessels, etc.

Target column:
Heart Diseases → 1 (Disease Present), 0 (No Disease)
🧠 Technologies & Libraries Used:
  Python 3
  Pandas and NumPy – Data manipulation
  Matplotlib and Seaborn – Data visualization
  Scikit-learn – ML modeling and evaluation
⚙️ How the Model Works:
   Load & Explore Data
   Preprocess Data (null check, encoding, scaling)
   Split into Train/Test Sets
   Train Logistic Regression Model
Evaluate with Metrics:
   Accuracy
   Precision
   Recall
   F1-Score
   ROC-AUC
Visualizations:
  Confusion Matrix
  ROC Curve

📊 Model Performance
Evaluation Metrics on Test Data:
Precision: ✅
Recall: ✅
F1-Score: ✅
ROC-AUC: ✅
✔️ Model shows good performance in predicting heart disease based on clinical indicators.
