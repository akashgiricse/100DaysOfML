# 100 Days Of ML - Log
## This is a round 2 of 100DaysOfCode challenge. In this round I'm mainly focusing on Machine Learning and Artificial Intelligence
<a name="toc"></a>
### Table of Contents 
|Day|Focus|Day|Focus|
|:---:|:-----:|:---:|:-----:|
|[Day 1](#day-1) **24/11/18**| Introduction to Machine Learnning. Supervised vs Unsupervised Learning. Model and Cost function. |[Day 2](#day-2) **25/11/18**| Linear regression with one variable. Gradient descent algorithm. Linear Algebra: Matrices and vectors. |
|[Day 3](#day-3) **26/11/18**| Multivariate Linear Regression. Features and Polynomial Regression. |[Day 4](#day-4) **27/11/18**| Computing Parameters Analytically: Normal Equation, Normal Equation Noninvertibility |
|[Day 5](#day-5) **28/11/18**| Octave/Matlab Tutorial |[Day 6](#day-6) **29/11/18**| _TODO_ |
|[Day 7](#day-7) **30/11/18**| _TODO_ |[Day 8](#day-8) **01/12/18**| _TODO_ |




----------
<a name="day-1"></a>
### Day 1: November 24, 2018 

**Today's Focus**: Introduction to Machine Learnning. Supervised vs Unsupervised Learning. Model and Cost function.

**Details**:

 - Started Andrew Ng's course "Machine Learning" on Coursera 
 - Supervised Learning: Dataset where we know the correct output, Unsupervised Learning: No idea what our result sould look like. 
 - Model Representation: Training set notation, Hypothesis function *h(x)*. 
 - Cost Function: To measure the accuracy of hpythesis function.
 - Contour plot: A contour plot is a graph that contains many contour lines. A contour line of a two variable function has a constant value at all points of the same line.


**Link to work**: [Here](https://github.com/akashgiricse/ml-andrew-ng)

[Table of Contents](#toc)


----------
<a name="day-2"></a>
### Day 2: November 25, 2018

**Today's Focus**: Linear regression with one variable. Gradient descent algorithm. Linear Algebra: Matrices and vectors.

**Details**:

 - Linear regression with one variable: Gradient descent algorithms. Learn how to use gradient descent algorithms on linear regression model.
 - Linear Algebra: Matrices and Vectors. Matrix-vector multiplication. Matrix-Matrix multiplication. Matrix multiplication properties: not commutative. Identity Matrix. Matrix inverse and Matrix transpose. 

**Link to work**: [Here](https://github.com/akashgiricse/ml-andrew-ng)

[Table of Contents](#toc)


----------
<a name="day-3"></a>
### Day 3: November 26, 2018 

**Today's Focus**: Multivariate Linear Regression. Features and Polynomial Regression.

**Details**:

 - Notation for multiple feature. Hypothesis function, cost function and Gradient descent for multiple feature. 
 - Feature Scaling: The main purpose of feature scaling is to make gradient descent obtain global optimum minima. We try to make every feature into -1 to +1 range. 
 - For feature scaling we use Mean Normalization.
 - Debugging: To make sure that our gradient descent is working correctly. And for that how to choose value of learning rate i.e. α. So basically we declare convergence if J(θ) i.e. Cost function decreases by less than 10^(-3). But this value is not fix. So we need to choose α such that the for every iteration, cost function is decreasing but also make sure that it's not decreasing very slow.
 - Features and Polynomial Regression: We can decrease the number of feature by combining then into one feature. For example, we can decrease **width** and **lenght** into **area**. We can also use polynomial regression to fit into out data set. 

**Link to work**: [Here](https://github.com/akashgiricse/ml-andrew-ng)

[Table of Contents](#toc)



----------
<a name="day-4"></a>
### Day 4: November 27, 2018

**Today's Focus**: Computing Parameters Analytically: Normal Equation, Normal Equation Noninvertibility

**Details**:

 - Normal Equation: Method to solve for θ analytically. 
 - How do we choose between Gradient Descent and Normal Equation to solve for θ.
 	- Gradient Descent when need to choose α, needs many iterations. This works well even when n(features) is large.
 	- Normal Equation when no need to choose α and don't need iteration. This algo slows down when the number of feature is very large because computation of **(X(transpose)X)inverse** has O(n3) (i.e Big Oh of N cube) complexity.
 - If **X(transpose)X** is non-invertible then generaly it is a sign that either we have redundant features (linearly dependent) or there are too many features.

**Link to work**: [Here](https://github.com/akashgiricse/ml-andrew-ng)

[Table of Contents](#toc)


----------
<a name="day-5"></a>
### Day 5: November 28, 2018

**Today's Focus**: Octave/Matlab Tutorial
**Details**:

 - Basic Operations, Moving data around, Computing on Data, Plotting data
 - Control and Conditional statements i.e. **for**, **while** and **if** statements.
 - Vectorization


**Link to work**: [Here](https://github.com/akashgiricse/ml-andrew-ng)

[Table of Contents](#toc)


----------
<a name="day-6"></a>
### Day 6: November 29, 2018

**Today's Focus**: _TODO_

**Details**:

 - _TODO_
 - _TODO_
 - _TODO_

**Link to work**: [_TODO_]()

[Table of Contents](#toc)


----------
<a name="day-7"></a>
### Day 7: November 30, 2018

**Today's Focus**: _TODO_

**Details**:

 - _TODO_
 - _TODO_
 - _TODO_

**Link to work**: [_TODO_]()

[Table of Contents](#toc)


----------
<a name="day-8"></a>
### Day 8: December 01, 2018

**Today's Focus**: _TODO_

**Details**:

 - _TODO_
 - _TODO_
 - _TODO_

**Link to work**: [_TODO_]()

[Table of Contents](#toc)
