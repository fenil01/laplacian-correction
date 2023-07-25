# laplacian-correction
Laplacian Correction:
The Naïve Bayes Classifier belongs to the family of probability classifier, using Bayesian theorem. The reason why it is called ‘Naïve’ because it requires rigid independence assumption between input variables.
Categorical data can be smoothed using the Laplace Smoothing approach in statistics. The Laplace Smoothing method is used to address the zero probability issue.
Steps for calculation:
•	Calculate the prior probability for given set of data 
•	Calculate Posterior Probabilities:
•	Put Prior and Posterior probabilities using following equation
 
The probability which is more accurate is considered.

This handles the problem of zero probability in Naïve Bayes. Using Laplace smoothing, we can represent P(w’|positive) as
 
Here, K stands for the number of dimensions (features) in the data, N for the number of reviews with y=positive, and alpha for the smoothing value.
The probability will no longer be zero even if a word is not present in the training dataset if we choose a value of alpha!=0 (not equal to 0).

To conclude, The Naive Bayes machine learning algorithm's zero probability issue is addressed by the smoothing method known as Laplace smoothing. The likelihood will be pushed closer to 0.5 by using larger alpha values, meaning that there is a chance that both positive and negative evaluations will have a word probability of 0.5.

