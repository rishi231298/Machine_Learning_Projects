This project focuses on predicting cardiovascular diseases using various machine learning algorithms. The primary goal is to build a robust and accurate predictive model that can assist in early diagnosis and preventive healthcare.
##Introduction
Cardiovascular diseases (CVDs) are one of the leading causes of death worldwide. Early detection can significantly reduce risks and improve treatment outcomes. This project applies various supervised machine learning algorithms to predict the presence of cardiovascular disease based on patient data.

## Dataset
The dataset used in this project contains medical and lifestyle information about individuals. Common features include:
*Age, in years
*Sex, 1 = male; 0 = female
*cp: chest pain type – Value 0: typical angina – Value 1: atypical angina – Value 2: non-anginal pain – Value 3: asymptomatic
*trestbps: resting blood pressure (in mm Hg on admission to the hospital)
*chol: serum cholestoral in mg/dAttribute Information:
*fbs: (fasting blood sugar > 120 mg/dl) 1 = true; 0 =false
*restecg: resting electrocardiographic results – Value 0: normal – Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of >0.05 mV) – Value 2: showing probable or definite left ventricu lar hypertrophy by Estes’ criteria
*thalach: maximum heart rate achieved during stress TEST
*exang: exercise induced angina, 1 = yes; 0 = no
*oldpeak = ST depression induced by exercise relative to rest
*slope: the slope of the peak exercise ST segment – Value 0: upsloping – Value 1: flat – Value 2: downsloping
*ca: number of major vessels (0-4) colored by flourosopy
*thal: thalassmia, 0 = null; 1=normal; 2 = fixed defect; 3 = reversible defect
*condition (target) : 0 = no disease, 1 = disease

Note:* The dataset must be preprocessed to handle missing values, encode categorical variables, and scale numerical features.

## Algorithms Used
The following machine learning algorithms were implemented and evaluated:

1. *K-Nearest Neighbors (KNN)*
2. *Support Vector Machine (SVM)*
3. *Logistic Regression*
4. *Decision Tree*
5. *Bagging Model*
6. *Random Forest*:
   - Using Entropy
   - Using Gini Index
7. *Gaussian Naive Bayes*
8. *Adaptive Boosting (AdaBoost)*
9. *Gradient Boosting*

Each algorithm was tuned for optimal performance using hyperparameter optimization techniques.

## Evaluation Metrics
The performance of the models was evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Area Under the Receiver Operating Characteristic Curve (AUC-ROC)

## Conclusion
This project demonstrates the application of machine learning algorithms to predict cardiovascular diseases. Ensemble methods like Random Forest and Gradient Boosting outperform simpler models, emphasizing the importance of advanced techniques in predictive analytics.
