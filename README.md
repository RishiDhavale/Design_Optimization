# Design_Optimization
<p align="center">
  <img width="460" height="300" src="https://uploads-ssl.webflow.com/5fb8c7611599e6f11e4853cb/5ff438a09f57bd0e2fa6b8e2_optimiztaion%20pic.png">
</p>

MAE598/494: Design Optimization covers mathematical modeling, optimization theory, and computational methods for analytical and simulation-based optimal engineering design. Key areas include:

- Unconstrained Optimization: Covers convexity, optimality conditions, gradient descent, convergence, modern line search techniques, Newton's method, and practical exercises.
- Supervised Learning: Involves ordinary least square, design of experiments, and practical applications.
- Constrained Optimization: Focuses on reduced gradient, KKT conditions, geometry sensitivity analysis, quasi-Newton methods, active set strategy, and Sequential Quadratic Programming.
- Optimal Control: Discusses Pontryagin’s Maximum Principle, Markov decision process, Bellman Equation, and practical applications.

## Homework 1
### Problem 
![Homework 1](https://github.com/RishiDhavale/Design_Optimization/assets/117399836/71af39d2-e1c9-4e63-afb2-fcc42c8e6ce0)

Homework 1 tackles a complex optimization problem, employing the SciPy.optimize library and JuMP for precision and efficiency. It delves into the intricacies of non-linear optimization, adeptly handling multiple constraints and sensitivities to initial conditions. The code not only computes optimal solutions but also offers insights into the impact of different starting points and constraint management, showcasing a robust approach to mathematical problem-solving.

## Homework 2
### Problem 
![Homework2](https://github.com/RishiDhavale/Design_Optimization/assets/117399836/04fd2c81-09da-4316-bc1c-3c59bb59b65b)

Homework 2, addresses a two-part optimization challenge in 3D space. Initially, it identifies the nearest point on the given plane to the given point, assessing the problem's convexity. The script then implements and compares gradient descent and Newton's algorithm, demonstrating their efficiency through various starting points and convergence analysis, culminating in a comprehensive log-linear plot to visualize algorithmic performance.

## Homework 3
### Problem 
![Homework3](https://github.com/RishiDhavale/Design_Optimization/assets/117399836/50456c52-c337-4d9d-8e6b-5b9b37307026)


Homework 3 is an implementation of the Generalized Reduced Gradient (GRG) algorithm in PyTorch, designed to solve given optimization problem with constraints. The objective function to be minimized is defined as the sum of the squares of three variables. The constraints include two functions, h1 and h2, which are set to equal zero. The GRG algorithm iteratively updates the variables to find the minimum of the objective function while satisfying the constraints. The final output of the code includes the minimized objective function value and the values of the variables that satisfy the constraints. This implementation showcases the use of PyTorch for differentiable programming in optimization problems.

## Homework 4
### Problem 
![Homework 4](https://github.com/RishiDhavale/Design_Optimization/assets/117399836/64a8f20a-b695-45b9-9c38-8c310f6f96ba)


## Homework 5
### Problem 1
![HW5_!](https://github.com/RishiDhavale/Design_Optimization/assets/117399836/d89d36fe-2856-473b-ab88-1cbc91664c44)

Homework 5 Problem 1, uses PyTorch to estimate parameters A12 and A21 in a vapor-liquid equilibrium problem involving a water-1,4 dioxane system. The problem is approached as a nonlinear least squares optimization, solved using gradient descent. The Antoine equation is utilized to calculate saturation pressures for both components at 20°C, and the script iteratively adjusts A12 and A21 to minimize the difference between predicted and actual pressures of the mixture at different compositions (x1). After optimization, the estimated values of A12 and A21 are displayed, along with the final loss indicating the fit quality. The results, both predicted and actual pressures, are then visually compared in a plot, demonstrating the model's performance against the provided data.

### Problem 2
![HW5_2](https://github.com/RishiDhavale/Design_Optimization/assets/117399836/fed46526-ff93-4292-8389-bb0131206988)
