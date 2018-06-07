# Iris

Initially took the Iris dataset, analyzed the data and realised that the problem was a supervised problem and the class labels
were categorical.Now that we know that the problem was categorical supervised problem was sure about applying the classification algorithm.There are many classification algorithms, question was which one to apply, so applied svm initially and then applied 
gridsearch along with k fold cross validation to find out the accuracy, the optimal values for the hyper parameters and also 
realised that the data was linearly distributed.


Note: 1)If the data is linearly distributed then we can apply Logistic Regression and SVM
      2)If the data distribution is not linear then we can apply decision tree, random forest, knn, Naive Bayes).
                   
Note: If the problem is find the probabilities of classes in specific then we can either use Logistic Regression
      and Naive Bayes ( Naive Bayes ---"Non linear" & Logistic Regression --- "Linear")
