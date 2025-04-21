# Mail-Detection
A machine learning project that detects whether a given email is spam or not. This project involves data preprocessing, model training, and evaluation using different ML algorithms.

# Data Collection 
The dataset used for this project was sourced from Kaggle in CSV file format. After loading the data, several preprocessing steps were performed to clean and transform the dataset according to the project's requirements.Unnecessary rows and columns that did not contribute to the classification task were also dropped. The target column was then labeled for binary classification, where emails marked as "spam" were assigned a value of 1, and those marked as "ham" (non-spam) were assigned a value of 0.


# Conclusion
In this project, we implemented two machine learning algorithms: Logistic Regression and Support Vector Machine (SVM) for email spam detection. Upon evaluation, Logistic Regression achieved an accuracy of 95% on both the training and testing datasets, indicating consistent and reliable performance. On the other hand, SVM showed a training accuracy of 99% and a testing accuracy of 95%, suggesting a stronger fit on the training data while maintaining similar generalization to unseen data. Both models demonstrated strong performance, with Logistic Regression offering a simpler yet effective solution, and SVM achieving higher training accuracy.
An evaluation was performed using various metrics, including the confusion matrix, F1-score, accuracy, precision, and recall to comprehensively assess the performance of the models.
