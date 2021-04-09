# Ensemble Methods

Ensemble methods (bagging, random forest and boosting) has been experimented. 
The “spambase” data set was used for the experiments. There are 57 features and two classes in this dataset: “spam” (label 1), and “nonspam” (label 0).


The classifiers to train are:
• One Decision Tree Classifier
• 50 Bagging Classifiers
• 50 Random Forest Classifiers
• 50 Adaboost Classifiers with decision stumps
• 50 Adaboost Classifiers with decision trees (max_leaf_nodes = 10)
• 50 Adaboost Classifiers with decision trees (no restriction)
