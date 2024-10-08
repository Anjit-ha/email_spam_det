# email_spam_det
email_spam_detection from scratch

Bayes' Theorem can be used as a classifier by following these steps:
Define the classes: Identify the classes you want to classify into (e.g., spam/not spam emails).
Gather training data: Collect a dataset with features (attributes) and corresponding class labels.
Calculate prior probabilities: Calculate the probability of each class (P(class)) based on the training data.
Calculate likelihoods: Calculate the probability of each feature given each class (P(feature|class)).
Apply Bayes' Theorem: Calculate the posterior probability of each class given the features (P(class|features)) using Bayes' Theorem:P(class|features) = P(features|class) * P(class) / P(features)Classify: Choose the class with the highest posterior probability as the predicted class.
