# Airline-Passenger-Referral-Prediction-Project
This project aims to predict whether airline passengers will recommend the airline to their friends and family based on their feedback and experience. The goal is to help airlines improve customer satisfaction and loyalty by identifying the key factors influencing passenger referrals.
# Approach
Data Preprocessing: Handled missing values using KNN imputation, encoded categorical variables, and addressed class imbalance using SMOTE oversampling.
Model Training and Evaluation: Trained and compared three machine learning models: Logistic Regression, Random Forest, and Support Vector Machine (SVM). Evaluated using accuracy, F1-score, precision, and recall.
Feature Importance Analysis: Analyzed the feature importance of the Random Forest model using permutation importance, revealing 'cabin_service', 'value_for_money', and 'entertainment' as the most influential factors.
Cross-Validation and Hyperparameter Tuning: Performed 5-fold cross-validation on the Random Forest model and tuned hyperparameters using GridSearchCV to optimize the F1-score.
# Results
The Random Forest model achieved the best performance with an accuracy of 0.93 and an F1-score of 0.92.
The model predicted that 46.05% of passengers will recommend the airline, closely matching the actual percentage of 46.15% in the dataset.
# Conclusion
The insights gained from this analysis can help airlines improve the customer experience and increase passenger referrals by focusing on the key influential factors identified by the Random Forest model. The comprehensive approach used in this project demonstrates the value of machine learning in understanding and predicting customer behavior in the airline industry.
