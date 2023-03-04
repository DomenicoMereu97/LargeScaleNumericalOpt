# Constrained Optimization Problem 
This report outlines the results of optimizing a Large-Scale problem in box contraints. The method used to obtain the results is the projected gradient method with backtrack as a line search strategy, using Exact Derivatives and Finite Differences.

Different techniques were explored. One of them was testing the effect of different contraction factors ρ on the descent rates in the backtracking algorithm. 

Another technique involved replacing the exact gradient with approximations using finite differences. A comparison was made between the central difference method and the forward difference method, and the results showed that the former performs better in terms of accuracy and avoiding premature stops.
