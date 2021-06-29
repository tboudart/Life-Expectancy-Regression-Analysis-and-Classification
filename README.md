# Life-Expectancy-Regression-Analysis-and-Classification
I contributed to a group project using the Life Expectancy (WHO) dataset from Kaggle where I performed regression analysis to predict life expectancy and classification to classify countries as developed or developing. The project was completed in Python using the pandas, Matplotlib, NumPy, seaborn, scikit-learn, and statsmodels libraries.

The regression models were fitted on the entire dataset, along with subsets for developed and developing countries. I tested ordinary least squares, lasso, ridge, and random forest regression models. Random forest regression performed the best on all three datasets and did not overfit the training set. The testing set R2 was .96 for the entire dataset and developing country subset. The developed country subset achieved an R2 of .8.

I tested seven different classification algorithms to classify a country as developing or developed. The models obtained testing set balanced accuracies ranging from 86% - 99%. From best to worst, the models included gradient boosting, random forest, Adaptive Boosting (AdaBoost), decision tree, k-nearest neighbors, support-vector machines, and naive Bayes. I tuned all the models' hyperparameters. None of the models overfitted the training set.

The data is from Kaggle and could be found at https://www.kaggle.com/kumarajarshi/life-expectancy-who

The Python libraries used include: pandas (1.2.3), matplotlib.pyplot
