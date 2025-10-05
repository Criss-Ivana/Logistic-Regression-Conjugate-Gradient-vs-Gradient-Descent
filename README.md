# Overview

This repository contains two implementations of logistic regression on a dataset containing exam scores and admission results. Both implementations use different optimization techniques:

1. Conjugate Gradient Optimization: This method uses the scipy.optimize.minimize function to find the optimal parameters (theta).

2. Gradient Descent: This method manually updates the parameters iteratively using the gradient descent algorithm.

Both models predict whether a student is admitted based on their Exam 1 and Exam 2 scores.

Graph:

<img width="546" height="413" alt="image" src="https://github.com/user-attachments/assets/20b65985-465c-4703-9b62-7b9eb247271f" />

Cost Function J(theta) History:

<img width="556" height="413" alt="image" src="https://github.com/user-attachments/assets/ed65b595-94cf-4a21-936b-548bdc02974d" />
