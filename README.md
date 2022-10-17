# Practical-Application-Assignment-17.1---Comparing-Classification
This is a study of comparing classifications with different parameters.

Following is the analysis process
  1. Dataset: https://archive.ics.uci.edu/ml/datasets/bank+marketing (Portuguese banking institution and is a collection of the results of multiple marketing campaign)
  2. Data were clean/dropped all the null/dropped duplicate data/convert classification (dependent) column from categorical to numerical (Yes/No to 1/0)
  3. Train and split the data - test_size = 0.2, random_state=21
  4. Numerical columns were scaled and catergorical columns were converted to numerical using one hot converter
  5. Imbalance was corrected by using SMOTE
  6. For baseline model Logistic Regression was considered
  7. Initially, using the default parameteres KNN, Decision Tree and SVC classification was considered to understand the perfromance and accuracy of the train and test models
  8. Then, Hyperparameters were considered to tune the classification to achieve better results
  9. Based on the results, simple method with default parameters produced similar accuracies compared to tuned classifications.
