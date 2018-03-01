# Logistic-Regression-Prediction

In **logistic regression**, the dependent variable is binary or dichotomous, i.e. it only contains data coded as 1 (TRUE, success, pregnant, etc.) or 0 (FALSE, failure, non-pregnant, etc.).

![Logistic Regression](https://user-images.githubusercontent.com/21111859/36820109-4fdc4424-1cba-11e8-92e4-366c4ccf2eca.png)

The goal of logistic regression is to find the best fitting (yet biologically reasonable) model to describe the relationship between the dichotomous characteristic of interest (dependent variable = response or outcome variable) and a set of independent (predictor or explanatory) variables. Logistic regression generates the coefficients (and its standard errors and significance levels) of a formula to predict a logit transformation of the probability of presence of the characteristic of interest:

_Logistic regression equation_

where p is the probability of presence of the characteristic of interest. The logit transformation is defined as the logged odds:

**Odds=p/(1-p)**

and

**Logit(p)=ln(p/(1-p))**

Rather than choosing parameters that minimize the sum of squared errors (like in ordinary regression), estimation in logistic regression chooses parameters that maximize the likelihood of observing the sample values.

#References: 
1) ![MedCalc](https://www.medcalc.org/manual/logistic_regression.php)
