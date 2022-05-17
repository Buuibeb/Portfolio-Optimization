# Portfolio-Optimization

# Background and problem statement
The optimal search for portfolio investment with stochastic constraint is a fundamental and complex problem in a financial market. It is important here for the investor to find the optimal proportion to allocate each share in a portfolio according to the classical measures of risk and return. 
The aim of the practical work is to write a program for optimising an investment portfolio with the objective of simultaneous risk minimization/return maximisation. Heuristic optimization techniques provide a new way for considering more practical and complex scenarios and settings without simplifying assumptions. They provide a useful trade-off between required computational time and quality of solution. Metaheuristics seem particularly suitable for practical portfolio optimization problems as these problems possess characteristics such as non-convex objective functions and search spaces.

#Our approach 
In our proposal, the portfolio should have 3-4 financial assets. We want to divide the money as a percentage in the assets so that we have the greatest possible fitness value, which should try to maximise the value and minimise the risk. As the fitness value we will use the Sharpe ratio, which counts with the values and risks, so we do not need to do multiobjective optimization. Data of values and risks will be taken from the internet.
Program should be able to solve the problem using different methods - hill-climbing, simulated annealing, genetic algorithms etc. State space is a set of all possible variations of how money can be divided into assets. With local search metaheuristics and genetic algorithms we will search through the state space and try to find the best solution. 
At the end we will compare different solutions and evaluate them. We should be able to tell which methods are better, which ones are faster or which ones keep getting stuck in local maximums.

#Sources:
https://github.com/naresh-dscience/Portfolio-Optimization-using-Genetic-Algorithm
https://www.researchgate.net/publication/322047252_Portfolio_Optimization_with_Metaheuristics/fulltext/5a405d2baca272d294527b8b/Portfolio-Optimization-with-Metaheuristics.pdf
https://ieeexplore.ieee.org/document/5609394
https://mpra.ub.uni-muenchen.de/41783/
