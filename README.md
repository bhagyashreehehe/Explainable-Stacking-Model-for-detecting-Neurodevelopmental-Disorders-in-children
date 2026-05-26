# Explainable-Stacking-Model-for-detecting-Neurodevelopmental-Disorders-in-children
 This project proposes an explainable stacking ensemble framework for the early detection of neurodevelopmental disorders in children using the 2024 National Survey of Children's Health (NSCH) dataset comprising 51,375 parent-reported records and 457 features.
A three-stage feature selection pipeline combining Variance 
Threshold, Chi-Square testing, and Random Forest importance 
was employed to reduce the feature space from 457 to 40 
clinically relevant variables, followed by Synthetic Minority 
Oversampling Technique (SMOTE) to address class imbalance. 
The framework was evaluated using traditional machine 
learning models namely Logistic Regression, Random Forest, 
XGBoost, and Support Vector Machine, combined through a 
stacking ensemble with Logistic Regression as the meta-learner 
for final prediction. Model performance was assessed using 
accuracy, precision, recall, F1-score, and ROC-AUC curves. 
This System overall shows how strong prediction tools plus clear 
reasoning can work together smoothly when testing young 
patients for brain development issues across clinics. 
