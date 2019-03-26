# Machine_learning
Different types of Machine Learning Algorithm Excercises 

# Clustering Techniques
Used Dataset Wine and Transactions/offers tabular dataset

We're trying to learn more about how our customers behave, so we can use their behavior 
(whether or not they purchased something based on an offer) as a way to group similar minded customers together.
We can then study those groups to look for patterns and trends which can help us formulate future offers.

In this case K-Means, Agglomerative Clustering works well.
Used ELBOW Method and Silhoutte Method to choose the number of clusters.
Visualizing Clusters using PCA.
Conclusion about different clusters.

# Naiive Bias
Done text analysis using a subset of movie reviews from the rotten tomatoes database.
Analysis of ratings/reviews given by critics to movies.
Tried Vector Space Model, Naiive Bias, Multinimial Naiive Bias. 
Divide in Training and Test Datasets(Cross-Validation Technique).
Tuning and searching the best Parameters.
Calculate the accuracy score on test and training set.
Applicaion of TF/IDF,LDA approaches.


# Logistic regression
Used Dataset of heights and weights of males and females to hone our understanding of classifiers.

Divide in Training and Test Datasets(Cross-Validation Technique).
When fitting models, we would like to ensure two things:
Found the best model (in terms of model parameters).
The model is highly likely to generalize i.e. perform well on unseen data.

Split the data into a training and test (hold-out) set.
Train on the training set, and test for accuracy on the testing set.

Tuning Hyperparameter.
For tuning the parameters of your model, you will use a mix of cross-validation and grid search. 
Here the most important parameter to tune is the regularization parameter C.
Calculating Accuracy.


# Linear Regression
Linear regression is used to model and predict continuous outcomes with normal random errors. 
Used Boston Housing data set that contains information about the housing price values of Boston.
EDA was done with plotting graphs using matplotlib and Seaborn libraries.
Fitting Linear Regression using statsmodel Library.
Telling Story about interpretation of Coefficients, Intercept, R^2, F-statistic, AIC was done.
Model Significance was tested.
