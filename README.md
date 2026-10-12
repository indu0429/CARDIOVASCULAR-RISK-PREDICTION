# CARDIOVASCULAR-RISK-PREDICTION



Cardiovascular Risk Prediction Using Ensemble Machine Learning, SHAP and LIME

1. Project Overview

This project is a Python-based desktop application that predicts cardiovascular risk using machine learning. It combines Random Forest and Gradient Boosting models and uses SHAP and LIME to explain the predictions.

Note: This is an educational prototype using synthetic demonstration data. It is not intended for medical diagnosis.

2. Project Objectives

- To predict cardiovascular risk using machine learning.
- To handle imbalanced training data using ADASYN.
- To combine Random Forest and Gradient Boosting.
- To explain predictions using SHAP and LIME.
- To display personalized results through a graphical user interface.

3. Technologies Used

- Python
- Tkinter
- Pandas
- NumPy
- Scikit-learn
- ADASYN
- SHAP
- LIME

4. Implementation

1. Generate 1,200 synthetic demonstration records.
2. Split the data into 80% training and 20% testing sets.
3. Apply ADASYN to the training data.
4. Train Random Forest and Gradient Boosting models.
5. Average the prediction probabilities from both models.
6. Predict one of four risk classes.
7. Use SHAP and LIME to explain the prediction.
8. Display the prediction and important features in the application.

5. Working Principle

Patient Input → Data Preparation → ADASYN → Random Forest + Gradient Boosting → Ensemble Prediction → SHAP and LIME → Personalized Result

6. Input Features

- Age
- Systolic Blood Pressure
- Diastolic Blood Pressure
- Body Fat Percentage
- Smoking Status
- Physical Activity

7. Risk Categories

- Low Risk
- Moderate Risk
- High Risk
- Very High Risk

These categories are generated using rules in the synthetic demo data and are not clinically validated.

8. Project Files

- "app.py" – Front end and prediction explanation.
- "model.py" – Data generation, model training and ensemble prediction.
- "requirements.txt" – Required Python libraries.
- "cardiovascular_demo_dataset.xlsx" – Optional demonstration dataset for reference.

Note: The current code generates its own synthetic data and does not directly load the Excel file.

9. How to Run

Install the required libraries:

"python -m pip install -r requirements.txt"

Run the application:

"python app.py"

10. Future Enhancement

- Use a suitable real clinical dataset.
- Add model evaluation metrics.
- Improve prediction explanations.
- Explore secure patient data storage.
- Perform proper clinical validation before any real-world healthcare use.

11. Disclaimer

This project is for educational purposes only. It uses synthetic data and must not be used for medical diagnosis or treatment decisions.
