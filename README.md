# Machine-Learning-Coursera-Stanford

This is the repository for my implementations on the Machine Learning course of Stanford University/Coursera.

Taught by [Andrew Ng](http://www.andrewng.org/)

### [Syllabus](https://www.coursera.org/learn/machine-learning/home/welcome)

## Linear Regression 
* [Linear Regression & Normal Equation](https://github.com/amancodeblast/machine-learning)
* Implemented linear regresion, mean square distance cost function and gradient descent.
* Example linear regression: 

![Linear Regression Plot](https://github.com/amancodeblast/machine-learning/blob/master/images/Linear_regression.png "Linear Regression Plot")
![Cost Function](https://github.com/amancodeblast/machine-learning/blob/master/images/Cost_function.png "Cost Function")


## Logistic Regression & Regularization
* [Logistic Regression & Regularization](https://github.com/amancodeblast/ML-practice-exercise-octave/tree/master/ex2)
* Implemented logistic regression, binary classification cost function and gradient descent.
* Implemented L2 regularization on cost function and gradient descent.

* Example of logistic regression classification:

![Logistic Regression Plot](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex2/images/Logistic_regression.png "Logistic Regression Plot")

* Example of L2 regularization: Shows how a low regularization term (0) results in overfitting and a large one (100) in underfiting, and lambda=1 showing the trade off minimizing the square mean distance or the weigth values, best fit for the model.

![Logistic Regression Plot with Lambda=0](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex2/images/Logistic_regression_reg_lambda_0.png "Logistic Regression Plot with Lambda=0")
![Logistic Regression Plot with Lambda=100](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex2/images/Logistic_regression_reg_lambda_100.png "Logistic Regression Plot with Lambda=100")
![Logistic Regression Plot with Lambda=1](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex2/images/Logistic_regression_reg_lambda_1.png "Logistic Regression Plot with Lambda=1")

## Bias/Variance
* [Logistic Regression & Regularization](https://github.com/amancodeblast/ML-practice-exercise-octave/tree/master/ex5)
* Implemented polynomial featurization, learning curve and validation curve plots.

![Learning curve over linear regression.](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex5/images/linear_regression_learning_curve.png "Learning curve over linear regression")
![Polynomial Regression over training data.](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex5/images/polynomial_regression.png "Polynomial Regression")
![Learning curve over polynomial regression.](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex5/images/linear_regression_learning_curve.png "Polynomial Regression over training data.")
![Validation curve over linear regression for Lambda selection.](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex5/images/linear_regresion_lambda_selection.png "Validation curve over linear regression for Lambda selection.")

## Support Vector Machine
* [SVM](https://github.com/amancodeblast/ML-practice-exercise-octave/tree/master/ex6)
* Implemented a SVM spam email classifier.

* Example of SVM Linear Kernel, overfitted with high C
![Example of SVM Linear Kernel, overfitted with high C](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex6/images/SVM_linear_kernel_high_C.png "Example of SVM Linear Kernel")
* Example of SVM Gaussian Kernel
![Example of SVM Gaussian Kernel](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex6/images/SVM_gaussian_kernel.png "Example of SVM Gaussian Kernel")

* Example of fitting a SVM: First image shows an underfit model for C=3, sigma=1. Second one, an overfitting model C=0.3, sigma= 0.03. And finally a good fit model C=0.3, sigma=0.1.
* Increasing C pushes to minimize the error from the cost function, where sigma in the Gaussian kernel if decreased pushes to minimize distance between the data point and landmark.

![SVM Underfit](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex6/images/SVM_spam_classifier_underfit_C3_sigma_1.png "SVM Underfit")
![SVM overfit](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex6/images/SVM_spam_classifier_overfit_C0_3_sigma_0_03.png "SVM Overfit")
![SVM good fit](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex6/images/SVM_spam_classifier_good_fit_C0_3_sigma_0_1.png "SVM good fit")


## K-means clustering and PCA
* [K-means clustering and PCA](https://github.com/amancodeblast/ML-practice-exercise-octave/tree/master/ex7)
* Implemeneted K-Means and PCA Algorithms.
* Example of K-Means centroid progression and point assigment: 1st Iteration and last 10th one.
![K-Means Iter=1](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex7/images/K-Means_example_iter1.png "K-Means Iter=1")
![K-Means Iter=10](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex7/images/K-Means_example_iter10.png "K-Means Iter=10")

* Example of PCA dimension reduction: Eigonvectors over data set, and projection of data point on the reduced dimension.
![PCA dim reduction](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex7/images/Eigonvectors%20over%20data%20set.png "PCA dim reduction")
![PCA projected](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex7/images/Projection%20over%20reduced%20dimension.png "PCA projected.")

* Example of K-Mean and PCA over data set: K-Means group assigment and PCA dimension reduction: 3-D to 2-D.
![3-D](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex7/images/K-Means%20over%203D%20data%20set.png "3-D")
![2-D](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex7/images/K-means%20data%20with%20PCA%20dim%20reduction.png "2-D")


## Anomaly Detection and Recommender Systems
* [Anomaly Detection and Recommender Systems](https://github.com/amancodeblast/ML-practice-exercise-octave/tree/master/ex8)
* Implemeneted anomaly detection with multi-variable gaussian distribution and recommender ystem.

* Example of anomaly detection. This plot shows the gaussian distribution and how the data points are placed, red circles show the anomalies, p(x; u, covariance) < epsilon.
![Anomaly detection](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex8/images/Mutlivariable%20gaussian%20distribution.png "Anomaly detection")

* Example of recommender system: "This dataset consists of ratings on a scale of 1 to 5. The dataset has nu = 943 users, and
nm = 1682 movies." This first plot shows the movie rating per user, second image shows how the system is able to find similar movies to the ones high rated by the same user. This is done after the implementation of the regularized cost, gradients, and training of the model.
![Recommender Systems](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex8/images/Movie%20reviews%20space.png "Recommender Systems")
![Recommender Systems](https://github.com/amancodeblast/ML-practice-exercise-octave/blob/master/ex8/images/System%20recommedation.png "Recommender Systems")
