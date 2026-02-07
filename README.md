# Machine-Learning-Project
This study presents a machine learning framework designed to predict employee promotion outcomes based on various performance metrics and demographic factors. By leveraging historical employee data, including performance reviews, tenure, skill assessments, and training participation, we developed a predictive model using algorithms such as Random Forest, Support Vector Machines (SVM), Decision Tree, and Logistic Regression. The model was trained and validated on our Employee Promotion Dataset. Our findings highlight the key factors influencing promotion decisions and demonstrate the potential of machine learning to enhance fairness and objectivity in talent management. This framework not only aids HR professionals in making informed promotion decisions but also fosters a culture of transparency and meritocracy within organizations. Future work will focus on refining the model and exploring its applicability across different industries to further validate its effectiveness.

# The objective of my project is to answer the following questions:
1.	Which machine learning model performs best for predicting employee promotions?
2.	Which machine learning techniques help to improve the accuracy of these predictions?
   
# RELATED WORK
“Employee Promotion end-to-end Solution” by Muhammad Imran Zaman (2023) compares the performance of six machine learning algorithms are decision trees, Random Forest, Bagging, XGB, AdaBoost and Gradient Boosting for employee promotion prediction.

# Model Training
Dividing my dataset into training and testing sets. test_size= 0.2, (20%) and train_size= 0.8 (80%). I have chosen four machine learning models to test the performance of machine learning model in predicting employee promotion.
As our dataset has imbalanced data after handling imbalanced data with random oversampling, synthetic minority over-sampling technique, random undersampling techniques implemented to take the minor data to equalise to major data in dataset. After this applying machine learning models to test the performance of the chosen machine learning models accuracy, f1-score, recall, precision.

# RESULTS
  
# Before hyperparameter tuning
ML MODEL	           ACCURACY
Logistic Regression	  0.92
Decision Tree	        0.88
Random Forest	        0.93
SVM	                  0.92

The performance of the decision tree was boosted by applying this hyperparameter tuning from 0.88 to 0.93.

# CONCLUSION
Our findings based on the research is after hyperparameter tuning the accuracy was changed for decision tree from 0.88 to 0.93. Random forest also performs same like decision tree = 0.93 accuracy. But for all the applied models have low recall values.
The implementation of this predictive framework not only enhances the objectivity and fairness of promotion decisions but also empowers organizations to recognize and nurture talent more effectively. By leveraging machine learning techniques, HR professionals can make informed decisions that align with organizational goals and foster a culture of meritocracy.

# FUTURE WORK
Future work related to an employee promotion dataset and the predictive modeling process, there are several avenues to explore that can enhance the analysis, improve model performance, and ensure the promotion process is effective and equitable. Here are some potential future work directions:
Advanced Modeling Techniques:   Deep Learning, Natural Language Processing (NLP). Scalability and Adaptability

# REFERENCE
Kaggle. (2019). HR Analytics: Employee Promotion Prediction. Retrieved from https://www.kaggle.com/datasets/arashnic/hr-ana
