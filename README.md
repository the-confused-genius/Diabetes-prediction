# Diabetes-prediction
This code will predict if the patient has Diabetes or not, depending on given features. We will be using the diabetes dataset which contains 768 observations and 9 variables, as described below:

pregnancies - Number of times pregnant.
glucose - Plasma glucose concentration.
BloodPressure - Diastolic blood pressure (mm Hg).
SkinThickness - Skinfold thickness (mm).
Insulin - Hour serum insulin (mu U/ml).
BMI – Basal metabolic rate (weight in kg/height in m).
DiabetesPedigreeFunction - Diabetes pedigree function.
Age - Age in years.
Outcome - “1” represents the presence of diabetes while “0” represents the absence of it. This is the target variable.
Evaluation Metric
We will evaluate the performance of the model using accuracy, which represents the percentage of cases correctly classified.

Mathematically, for a binary classifier, it's represented as accuracy = (TP+TN)/(TP+TN+FP+FN), where:

True Positive, or TP, are cases with positive labels which have been correctly classified as positive.
True Negative, or TN, are cases with negative labels which have been correctly classified as negative.
False Positive, or FP, are cases with negative labels which have been incorrectly classified as positive.
False Negative, or FN, are cases with positive labels which have been incorrectly classified as negative.
