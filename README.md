# Convex Optimization In Python

Python Implementations For Examples in Textbook Convex Optimization 1

Every jupyter notebook can be run in colab by replacing the Github link to the notebook by `colab.research.google.com/github` (see the below links).

## Notebook Titles

| Notebook | Title |
|---|---|
| `S9.3.2_F9.2_NL09.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S9.3.2_F9.2_NL09.ipynb) | Demo: A minimization on a quadratic problem in $R^2$ |
| `S9.3.2_F9.3_F9.4_F9.5_NL10.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S9.3.2_F9.3_F9.4_F9.5_NL10.ipynb) | Demo: A minimization on a non-quadratic problem in $R^2$ |
| `S9.3.2_F9.6_NL13.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S9.3.2_F9.6_NL13.ipynb) | Demo: A minimization of a log-barrier function, $f(x)=c^T x -\displaystyle{\sum_{i=1}^{m}}\log(b_i-a_i^Tx)$, with $m=n=1$ |
| `S9.3.2_F9.6_NL14.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S9.3.2_F9.6_NL14.ipynb) | Demo: A minimization of a log-barrier function, $f(x)=c^T x -\displaystyle{\sum_{i=1}^{m}}\log(b_i-a_i^Tx)$, with $m=n=2$ |
| `S9.3.2_F9.6_NL17.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S9.3.2_F9.6_NL17.ipynb) | Demo: The influence to the convergence rate for different $\alpha, \beta$ for the gradient method applied to log barrier function |
| `S9.4.2_E9.2_NL18.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S9.4.2_E9.2_NL18.ipynb) | Demo: solving the geometric program: \textit{Frobenius norm scaling} |
| `S9.4.4_F9.11_F9.12_F9.13_F9.14_F9.15_NL19.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S9.4.4_F9.11_F9.12_F9.13_F9.14_F9.15_NL19.ipynb) | Demo: the relations between the steepest descent for quadratic norm and the change of coordinate |
| `S9.5.4_F9.19_F9.20_NL20.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S9.5.4_F9.19_F9.20_NL20.ipynb) | Demo: Newton's method on the non-quadratic problem in $R^2$ |
| `S9.5.4_F9.21_F9.22_NL21.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S9.5.4_F9.21_F9.22_NL21.ipynb) | Demo: Newton's method on the log-barrier function in $R^{100}$ |
| `S9.5.4_F9.23_NL22.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S9.5.4_F9.23_NL22.ipynb) | Demo: An experiment on Newton's method implementation on an example in $R^{5000}$ |
| `S9.5.4_NL23.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S9.5.4_NL23.ipynb) | Demo: An Experiment on Affine Invariance in Newton's Method |
| `S9.6.5_Figure9.25_NL24.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S9.6.5_Figure9.25_NL24.ipynb) | Demo: An Experiment on Convergence Rate on A Family of Self-Concordant Function |
| `S9.7.2_E9.9_NL29.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S9.7.2_E9.9_NL29.ipynb) | (NA) |
| `S9.7.2_Equ9.60_NL28.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S9.7.2_Equ9.60_NL28.ipynb) | Demo: An Experiment on Exploiting the Diagonal plus Low Rank Structure |
| `S10.3.5_F10.1_F10.2_NL25.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S10.3.5_F10.1_F10.2_NL25.ipynb) | Demo: Solving Equality Constrained Analytic Center By Infeasible Start Newton Method - I : Feasible and Lower Bounded Problem |
| `S10.3.5_F10.3_F10.4_NL26.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S10.3.5_F10.3_F10.4_NL26.ipynb) | Demo: Solving Equality Constrained Analytic Center By Infeasible Start Newton Method - 2 : Infeasible or Unbounded Problem |
| `S10.3.5_F10.5_NL27.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S10.3.5_F10.5_NL27.ipynb) | Demo: Solving Convex-Concave Game via Infeasible Start Newton Method |
| `S10.4.3_Analytic_Center_LMI_NL38.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S10.4.3_Analytic_Center_LMI_NL38.ipynb) | Demo: Solving Analytic Center of a Linear Matrix Equality |
| `S10.4.3_F10.6_F10.7_F10.8_NL36.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S10.4.3_F10.6_F10.7_F10.8_NL36.ipynb) | Demo: Experiments on Three Methods in Solving the Equality Constrained Analytic Centering Problem |
| `S10.4.3_Optimal_Control_NL39_NL40.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S10.4.3_Optimal_Control_NL39_NL40.ipynb) | Demo: From Newton Method to Riccati Recursion in solving Linear Quadratic Regulator (LQR) |
| `S10.4.3_Optimal_Network_Flow_1_NL37.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S10.4.3_Optimal_Network_Flow_1_NL37.ipynb) | Demo: Further Readings on Optimal Network Flow |
| `S10.4_E10.3_NL31.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S10.4_E10.3_NL31.ipynb) | Demo: Solve KKT System via Block Elimination |
| `S10.4_E10.4_NL32.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S10.4_E10.4_NL32.ipynb) | Demo: Solve Minimum Length Piecewise-Linear Curve Subject to Equality Constraints |
| `S10.4_E10.4_NL34.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S10.4_E10.4_NL34.ipynb) | Demo: Further experiments on Solving Minimum Length Piecewise-Linear Curve Subject to Equality Constraints |
| `S10.4_E10.4_NL35.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S10.4_E10.4_NL35.ipynb) | Demo: Experiments on using Block Elimination on Solving Minimum Length Piecewise-Linear Curve Subject to Equality Constraints |
| `S11.2.2_E11.1_Figure11.2_NL30.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.2.2_E11.1_Figure11.2_NL30.ipynb) | Demo: The Central Path in Inequality form Linear Programming |
| `S11.3.2_F11.4_F11.5_NL33.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.3.2_F11.4_F11.5_NL33.ipynb) | Practice: An Experiment on Solving Linear Programming in Inequality Form by the Barrier Method |
| `S11.3.2_F11.6_NL41.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.3.2_F11.6_NL41.ipynb) | Demo: Solving Geometric Programming by Barrier Method |
| `S11.3.2_F11.6_NL42.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.3.2_F11.6_NL42.ipynb) | Demo: Further Experiments on Barrier Method Convergence in Solving the Geometric Programming |
| `S11.3.2_F11.7_F11.8_NL43.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.3.2_F11.7_F11.8_NL43.ipynb) | Demo: Using Barrier Method to Solve a Family of Standard Form LPs |
| `S11.4.1_E11.4_F11.9_NL44.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.4.1_E11.4_F11.9_NL44.ipynb) | Demo: Further Experiments on Comparison of Phase I methods |
| `S11.4.3_F11.10_F11.11_NL45.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.4.3_F11.10_F11.11_NL45.ipynb) | Demo: Further Experiments on Solving A Family of Linear Feasibility Problem by Basic Phase I Method |
| `S11.4.3_F11.12_NL46.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.4.3_F11.12_NL46.ipynb) | Demo: Further Experiments on Feasibility Detection Using Infeasible Start Newton Method |
| `S11.6.3_F11.15_F11.16_NL50.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.6.3_F11.15_F11.16_NL50.ipynb) | Demo: Further Experiments on Solving SOCP by Barrier Method |
| `S11.6.3_F11.17_F11.18_NL47.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.6.3_F11.17_F11.18_NL47.ipynb) | Demo: Further Experiments on Solving a Small SDP by Barrier Method |
| `S11.6.3_F11.19_Fs11.20_NL51.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.6.3_F11.19_Fs11.20_NL51.ipynb) | Demo: Further Experiments on Solving A Family of SDP by Barrier Method |
| `S11.6.3_NL48.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.6.3_NL48.ipynb) | Demo: Further Experiments on Solving a Small SDP by Barrier Method -- II (continue.) |
| `S11.6.3_NL49.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.6.3_NL49.ipynb) | Demo: Further Experiments on Solving a Small SDP by Barrier Method -- III (continue.) |
| `S11.7.4_F11.21_NL52.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.7.4_F11.21_NL52.ipynb) | Demo: Further Experiments on Solving A Small Linear Programming by  Primal-Dual Interior-Point Method |
| `S11.7.4_F11.22_NL53.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.7.4_F11.22_NL53.ipynb) | Demo: Further Experiments on Solving Geometric Programming by  Primal-Dual Interior-Point Method |
| `S11.7.4_F11.23_NL54.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.7.4_F11.23_NL54.ipynb) | Demo: Further Experiments on Solving A Family of LP by  Primal-Dual Interior-Point Method |
| `S11.8.1_NL55.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.8.1_NL55.ipynb) | Demo: Further Experiments on Solving A Family of LP by Barrier Method |
| `S11.8.2_NL56.ipynb` [Open in colab](https://colab.research.google.com/github/leputz/ConvexOptimizationInPython/blob/main/S11.8.2_NL56.ipynb) | Demo: Further Experiments on Solving $l_1$-norm approximation by Barrier Method |

The objective of this repository is to assist the reader to gain practical experience of the convex optimization theory, by first reproducing the examples and the figures in the textbook ([book-convex-2004]) by Python, and then by tuning the model parameters for further comparing the characteristics of the convex problems and their solutions. These characteristics include,

- The possible variations and restrictions of the convex problems
- The convergence rate
- The uniqueness of the optimal solution
- The bounds of the optimal value
- The feasibility and infeasibility of the problems
- The challenges in numerical implementations

The reader will also learn how to implement and verify the algorithm through the guidance of the convex optimization theory itself. The textbook ([book-convex-2004]) has been popularly used in many open courses about convex optimization, including Engineering Everywhere open course, [https://see.stanford.edu/Course/EE364A](https://see.stanford.edu/Course/EE364A)

However, many learners from the convex optimization course have been complaining that time is insufficient to deep dive into the details of the algorithms. I hope this repository will help learners catch the essential of the convex optimization theory without writing the algorithms from the scratch for practice and verification. Readers are encouraged to use this repository as the supplementary material for the course.