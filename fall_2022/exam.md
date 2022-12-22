# Exam

## Question 1
1. Compare PCA and Truncated SVD. In which cases each algorithm suits the best?
2. Compare Logistic Regression and SVM classifiers. 
3. Compare DBSCAN and k-Means clustering algorithms.
4. Compare AUC and F1 metrics for binary classification.
5. What assumptions about data distribution should we consider to apply PCA effectively?
6. What assumptions about data is necessary to be able to use k-Means clustering? 
7. What happens with the norm of weights in the linear models, if you train them with $L_2$ regularization? What happens with the weights in the linear models, if you train them with $L_1$ regularization? In which cases this effect in $L_1$ can be useful?
8. Why a bagging ensemble works? How is it connected with bias-variance decomposition? Provide derivation.
9. Suppose you have Random Forest model and Gradient boosting model, each with 100 decision trees. Which model will profit better by adding 1 more tree in the ensemble?
10. How bias and variance of the NN model change during traing? Why?
11. You have trained a ML model, but the loss on validation set is not good enough. The loss on the train set is even worse. What is the best single way to improve the model?  
12. What is size of the gradient in Gradient Boosting algorithm? Why?
13. Is it effective to use linear models in boosting ensemble?  Why?
14. Is it possible to reach exact local minima using SGD?  Why?
15. How effectiveness of BatchNorm depends on the batch size?
16. Why it is not recommended to initialize all the weights in NN with 0?
17. Suppose you want to check arithmetics on the embeddings from Word2Vec model. For example, $\Delta = ||E(queen) - (E(king) + (E(woman) - E(man))) ||$. How $\Delta$ depends on the frequency of words used in delta in text corpus? 
18. What are dead neurons regarding RELU activation and why are they bad?

## Question 2

1. What is asymptotic time complexity of analytic solution for linear regression with MSE loss? Explain the derivation.
2. What is asymptotic time complexity of training and inference in a decision tree? Explain the derivation.
3. What is asymptotic time complexity of training k-Means? Explain the derivation.
4. Compare properties of the solutions of linear regression with MSE loss and 2-layer perceptron for regression task without activation function $y = X W_1 w_2$.
5. You have multilayer perceptron $y = W \sigma (WX)$ with sigmoid function $\sigma(z)=\frac 1 {1 + e^{-z}} $ and shared weights $W$. Compute the derivative $ \frac {dy} {dW}$. 
6. You train linear regression with MSE loss and $L_2$ regularization with SGD. Write the equation of update of weights $w_t$ on timestep t.