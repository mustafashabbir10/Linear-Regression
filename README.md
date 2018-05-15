# Linear-Regression-

This example project demonstrates how Gradient Descent Algorithm may be used to solve Linear Regression problem as Opposed to solving it by Scikitlearn. 

## Description-

#### Gradient Descent-
Gradient descent is a first-order iterative optimization algorithm for finding the minimum of a function. To find a local minimum of a function using gradient descent, one takes steps proportional to the negative of the gradient (or approximate gradient) of the function at the current point.
Update Equations-
The objective of linear regression is to minimize the cost function 

where hypothesis is given by the linear model-

The parameter of the model are theta values. These are the values I will adjust to minimize the cost function. The most common way to do it is by batch gradient descent. In batch gradient descent, each iteration performs the update

With each step of gradient descent, the parameters thets come close to the optimal values that will achieve the lowest cost.


### Output-
As we perform gradient descent to learn minimize the cost function, it is helpful to monitor convergence by computing the cost. The graph below shows the convergence of the cost function.

This graph above clearly shows that graident descent has converged.
The graph below shows the regression line fitted from Gradient Descent and Scikit-Learn. It can be clearly seen that both of these overlap and are nearly the same.