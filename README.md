# Diabetes-prediction
This code will predict if the patient has Diabetes or not, depending on given features. We will be using the diabetes dataset which contains 768 observations and 9 variables, as described below:

1. pregnancies - Number of times pregnant.
2. glucose - Plasma glucose concentration.
3. BloodPressure - Diastolic blood pressure (mm Hg).
4. SkinThickness - Skinfold thickness (mm).
5. Insulin - Hour serum insulin (mu U/ml).
6. BMI – Basal metabolic rate (weight in kg/height in m).
7. DiabetesPedigreeFunction - Diabetes pedigree function.
8. Age - Age in years.
9. Outcome - “1” represents the presence of diabetes while “0” represents the absence of it. This is the target variable.

Evaluation Metric
We will evaluate the performance of the model using accuracy, which represents the percentage of cases correctly classified.

Mathematically, for a binary classifier, it's represented as accuracy = (TP+TN)/(TP+TN+FP+FN), where:

1. True Positive, or TP, are cases with positive labels which have been correctly classified as positive.
2. True Negative, or TN, are cases with negative labels which have been correctly classified as negative.
3. False Positive, or FP, are cases with negative labels which have been incorrectly classified as positive.
4. False Negative, or FN, are cases with positive labels which have been incorrectly classified as negative.
