Credit Card Fraud Detection Project

##Overview

This project is dedicated to the development of a credit card fraud detection system using machine learning techniques. The primary aim is to create an efficient model capable of accurately identifying fraudulent credit card transactions within a dataset.

##Project Highlights

Algorithm Selection: Logistic regression was chosen as the machine learning algorithm for its proven effectiveness in binary data classification tasks.
Dataset: The dataset, sourced from Kaggle, comprises approximately 28,500 transactions. Among these, only 492 transactions are classified as fraudulent (denoted by the class value 1), while the remaining are legitimate transactions (class value 0).

Data Imbalance Mitigation: To address the severe data imbalance, an undersampling method was employed. This technique involved randomly selecting 492 legitimate transactions from the dataset to create a balanced dataset with an equal number of legitimate and fraudulent transactions.

Model Training and Testing: The model was then trained on the balanced dataset and evaluated against a test dataset. The achieved model efficiency was a commendable 90%, demonstrating its ability to effectively distinguish between legitimate and fraudulent transactions.

##Future Improvements

For future enhancements of this project:

Exploring Random Forest Regressor: An exploration into the use of the Random Forest Regressor is planned. This algorithm is known for its robust performance with highly imbalanced datasets and may offer even better results.
Oversampling Experimentation: As an alternative to undersampling, future work will involve experimenting with oversampling techniques to address data imbalance.

##Conclusion

In summary, this credit card fraud detection project successfully leveraged logistic regression to create a high-performing model that achieved an impressive 90% efficiency in identifying fraudulent transactions. This work holds significant potential in the financial sector for minimizing fraud-related losses.


########    ADDED ANOTHER FILE     ##########
In Anomaly Detection file I have used Isolation Forest Algorithm to increase the accuracy of the model to 99.74%.
