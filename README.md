# Google Summer of Code 2022

## Organisation: The R Project for Statistical Computing
## StochOptim - An R wrapper for stochastic and global optimization tools

### Test 1 (Easy) - Coding functions

Prepare R code for three of the unconstrained test functions in GO Test Problems that allow dimension greater than 4

### Test 2 (Easy) - optim()

Try to minimize these with the base R optim() function. Be sure to document what you do.

### Test 3 (Moderate) - optimx

Check that your code from part 2 will run with the optimr() wrapper. Then run several (at least 4) solvers at once with the opm() function. Justify your choice of solvers for each of the problems. Comment briefly on the output.

### Test 4 (Moderate) - Stochastic solvers

Choose at least three stochastic optimization solvers from the suggestions in Global and Stochastic Optimization section of the CRAN Task View: Optimization and Mathematical Programming and apply these to your test problems. Comment briefly on why you chose particular solvers, on any issues in setting up your calculations and on the output observed.

### Test 5 (Moderate) - Volcano function

Prepare R code for the volcano function of two parameters b=c(x,y) that is defined as

f(d) = (10 - 0.5*d) + sin(2*d) where d is the square norm distance from x=1, y=5.

What are the likely issues in minimizing this function over the two dimensions? A [3D] perspective plot may help you. Do solvers have trouble getting sensible results for this function?
