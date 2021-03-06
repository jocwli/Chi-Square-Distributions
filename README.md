# Chi-Square-Distributions
### Repo Project:
- Dataset used:
- What sampling was done?
- Null Hypothesis:
- Alternative Hypothesis:
- Alpha level:
- Results:

## Background
### When should we use Chi-square distributions for modeling?
Chi-squared distributions are used with continuous data.
1. Chi-square distributions most commonly is used in hypothesis testing:
  - Test goodness of fit: tests whether observed frequency fits expected frequency distribution that is based on theoretical/ known probability of each outcome
    - Null= data is consistent, population frequencies equal expected frequencies
    - Alternative= data is not consistent
  
  - Test independence: 
    - Null= 2 variables are indpendent
    - Alternative= 2 variables are dependent
  - Determines critical regions and confidence intervals
2. Chi-square distributions can find probabilities associated to the critical values 
  - For example...

### Limitations using Chi-square
- It only pertains to probability of existence of a relationship in variables
- It can be misinterpreted as strength of relationships, it doesn't account for magnitude
- It should be used in combo with other techniques

### Statistical definition of Chi-square statistic
The Chi-square statistic compares the frequencies of observed with expected throughout a contingency table. The greater the departure of two frequencies, means the greater the confidnce that there exists a relationship between two variables.

Chi-square statistic = SUM((expected - observed)^2 / expected)

Hypothesis Testing rules:
- If chi-square value > chi-square distribution, then reject Null Hypothesis.
- If chi-square value < chi-square distribution, then accept Null Hypothesis.

### Statistical definition of Chi-square distributions
These mathematical elements are important to understand which R functions to code. Chi-square distributions are special cases of Gamma distributions and are positively skewed with support of x>=0.

Mathematical notation is X~ Gamma(r/2, 2) or X~ X^2(r), where alpha= r/2, theta = 2, r = degrees of freedom.

PDF of Chi-square = f(x)= (1/ Gamma (r/2) 2^(r/2)) x^(r/2 -1) (e^(-x/2))

Mean of Chi-square = (r/2)(2) = r

Variance of Chi-square = (r/2)(2)^2 = 2r

MGF of Chi-square= (1-2t)^(r/2) for t <1/2

CDF of Chi-square= F(x) = P(X<=x) = integral x to 0 ((1/ Gamma (r/2) 2^(r/2)) x^(r/2 -1) (e^(-t/2)) dt

