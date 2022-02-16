# gridSearch-parameter-tuning-on-various-classification-model
using Grid search algorithm with cross validation to tune parameters and training for various classification models and compare between them 
this research aplied on digits by sklearn datasets


used models with tuned parameters
1-svm  (C,kernel)
2-random forest  (n_estimators)
3-logistic regression  (C)
4-naive_bayes.GaussianNB  (var_smoothing)
5-naive_bayes.MultinomialNB  (alpha)
6-DecisionTree  (criterion)

and used 5 folds for cross validation

result 
1	svm	                  scored:94.7697%	  with   parameters values ={'C': 1, 'kernel': 'linear'}
2	random_forest	        scored:93.9362%	  with   parameters values ={'n_estimators': 100}
3	logistic_regression	  scored:92.2114%	  with   parameters values ={'C': 1}
4	nbm	                  scored:87.0350%	  with   parameters values ={'alpha': 0}
5	dt	                  scored:81.0258%	  with   parameters values ={'criterion': 'entropy'}
6	nbg	                  scored:80.6928%	  with   parameters values ={'var_smoothing': 1e-09}
