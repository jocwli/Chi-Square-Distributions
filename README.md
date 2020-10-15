# Chi-Square-Distributions
## What are chi-square distributions?
Chi-square distributions are special cases of Gamma distributions and are positively skewed with support of x>=0.

Mathematical notation is X~ Gamma( r/2, 2) or X ~X^2(r), where alpha= r/2, theta = 2, r = degrees of freedom.

PDF of Chi-square = f(x)= (1/ Gamma (r/2) 2^(r/2)) x^(r/2 -1) (e^(-x/2))

Mean of Chi-square = (r/2)(2) = r
Variance of Chi-square = (r/2)(2)^2 = 2r

MGF of Chi-square= (1-2t)^(r/2) for t <1/2

## When should we use Chi-square distributions for modeling?
1. Chi-square distributions can be used to find the probabilty
2. Test population variance
3. Test goodness of fit in categorical data
4. Test independence
