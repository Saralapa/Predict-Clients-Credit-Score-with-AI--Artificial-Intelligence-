# Artificial Intelligence and Predictions
## Case: Customer Credit Score
You have been hired by a bank to determine the credit score of its customers. You need to analyze all the bank's customers and, based on this analysis, create a model that can read customer information and automatically determine their credit score: Poor, Standard, Good

## Data Preprocessing
The data is imported from the "clients.csv" file and displayed. String columns such as "occupation," "credit_mix," and "payment_behavior" are encoded into integer elements using the LabelEncoder class. The encoded table is then displayed.

## Model Training and Evaluation
The data is split into training and test sets using the train_test_split function. Two models are trained on the training dataset: a RandomForestClassifier model and a KNeighborsClassifier model. The accuracy scores of both models are calculated and displayed. The RandomForestClassifier model achieved an accuracy of approximately 82%, while the KNeighborsClassifier model achieved an accuracy of approximately 73%.

## Model Selection and Prediction
Based on the higher accuracy achieved, the Decision Tree model (RandomForestClassifier) is selected for predicting the credit scores of new clients. The "new_clients.csv" file is imported, and the string columns are encoded. The trained Decision Tree model is then used to predict the credit scores for the new clients, and the predictions are displayed.
