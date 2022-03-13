# MannKendall.jl
The non-parametric Mann-Kendall test and Sen's Slope for Julia Programming Language

# Example
```julia
using MannKendall
y = rand(40*12)
x = collect(1:length(y))
mann_kendall(x,y)                                                                                                                                              
(reject_null_hypothesis = false, p_value = 0.4369827573849885, Tau = -0.02374739039665971, slope = -7.613151196044908e-5, intercept = 0.5150870782436969)
```

# Note
Another M-K test is also available (https://github.com/mmhs013/MannKendall.jl), but I like this one for which x is the parameter for time but the vector of time does not have to be in the same interval. 

# Usage: 
Since the other M-K package is already registered and take the name "MannKendall", this one is renamed to MannKendall_XY.
