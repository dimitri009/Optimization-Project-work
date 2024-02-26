# Project Summary

This project focuses on evaluating the performance of optimization techniques, specifically Gradient Descent and Newton's Method, on logistic regression problems. The goal is to implement classes and functions in Python, utilizing the NumPy library, to load data and build instances of L2-regularized logistic regression problems. Additionally, the project aims to conduct experiments on real-world datasets to measure the efficiency of the methods in terms of convergence, runtime, and accuracy.

**Introduction**

*Logistic regression* is a widely used statistical model for binary classification tasks, predicting the probability of an instance belonging to a particular category. It utilizes the logistic function to transform outputs into probabilities and adjusts parameters through optimization to maximize prediction accuracy. Regularization is often employed to prevent overfitting.

**Optimization Methods**

The project explores three optimization methods: *Gradient Descent with Armijo Step Size*, *Newton's Method*, and *Conjugate Gradient Method*. These methods are applied iteratively to minimize the logistic loss function, considering second-order information like gradients and Hessians.

**Experiments**

Experiments are conducted on diverse datasets including Breast Cancer, Ionosphere, Diabetes, Wine Quality, and Rice varieties. Metrics such as *final cost value*, *runtime*, *iterations*, and *accuracy* are compared across the optimization methods to evaluate their performance.

**Results and Conclusion**

Newton's Method demonstrates superior convergence speed but may face challenges in achieving high accuracy and entails significant computational costs. The Conjugate Gradient Method emerges as a balanced alternative, offering efficiency in minimizing loss values and accuracy comparable to or better than Gradient Descent while being less computationally demanding than Newton's Method.

**Conclusion**

Choosing the most suitable optimization method for logistic regression involves considering trade-offs between convergence speed, computational efficiency, and accuracy. The Gradient Conjugate Method is highlighted as a robust choice, but the decision should be tailored to the dataset and available computational resources.
