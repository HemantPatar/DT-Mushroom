# Mushroom
Mushroom classification 

Data set size 8124 rows × 23 columns.

Data cleaning & data visualization for model training.

Seprating input and output from dataset.

Normalise the input using dummies to convert into integers.

Standardised using StandardScaler.

Normalise the target class using LabelEncoder to convert into integers.

Train test split.

Use(LogisticRegression,KNN classifier,DecisionTreeClassifier,RandomForestClassifier,SVC)

LogisticRegression  
Find Mean f1 score & standard deviation score for logistic classifier

KNN classifier find best parameters (n_neighbors) using GridSearchCV  
find max r2 score for KNN classifier
Find Mean f1 score & standard deviation score for KNN classifier

DecisionTreeClassifier
Find Mean f1 score & standard deviation score for DecisionTreeClassifier

RandomForestClassifier find best parameters (n_estimators) using GridSearchCV  
find max r2 score for RandomForestClassifier
Find Mean f1 score & standard deviation score for RandomForestClassifier

SVC find best parameters (C, kernel) using GridSearchCV  
find max r2 score for SVC
Find Mean f1 score & standard deviation score for SVC

Use SVC.

Get confusion matrix,f1 score, classification report,AUC ROC score.

Save model (pickle).
