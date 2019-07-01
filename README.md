# Linear-Regression-Model
Linear Regression model

This contains python version of Linear Regression model. This is based off of Linear Regression model assignment from Andrew NG's course which was in Octave.

This expects an input file ex1data1.txt that was provided as part of the course. This file contains data pertaining to population of a city and profit made by food truck.

The goal of the regression is to identify theta values that will minimize the cost. 

Cost is computed 
J(θ) = 1/(2*m) Sum(hθ(x(i)) − y(i)^2

where the hypothesis hθ(x) is given by the linear model
hθ(x) = θ0 + θ1x1

Hence the program strives to identify θ0 and θ1 to minimize the cost
