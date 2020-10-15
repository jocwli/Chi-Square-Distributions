# Chi-Square-Distributions
## When should we use Chi-square distributions for modeling?
1. Chi-square distributions can be used to find the probabilty of the 
2. Test population variance
3. Test goodness of fit in categorical data
4. Test independence

The chi-square distribution is used in many cases for the critical regions for hypothesis tests and in determining confidence intervals. 

## Repo Project using Chi-square distribution


## Statistical definition of Chi-square distributions
Chi-square distributions are special cases of Gamma distributions and are positively skewed with support of x>=0.

Mathematical notation is X~ Gamma(r/2, 2) or X~ X^2(r), where alpha= r/2, theta = 2, r = degrees of freedom.

PDF of Chi-square = f(x)= (1/ Gamma (r/2) 2^(r/2)) x^(r/2 -1) (e^(-x/2))

Mean of Chi-square = (r/2)(2) = r

Variance of Chi-square = (r/2)(2)^2 = 2r

MGF of Chi-square= (1-2t)^(r/2) for t <1/2

CDF of Chi-square= F(x) = P(X<=x) = integral x to 0 ((1/ Gamma (r/2) 2^(r/2)) x^(r/2 -1) (e^(-t/2)) dt

