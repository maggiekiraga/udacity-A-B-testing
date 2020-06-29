# Udacity A/B testing
### Is the new web design associated with higher enrollment rates? Running A/B probability tests to help company determinate the value of a new web design. 


## Task Description:
The task of this project was to help make the decision if a change in the web design would increase the number of users purchasing the company's products. 

## The Aim of the Project:
The aim of this project was to, based on responses of the control versus the experimental group of users, determine the statistical significance of launching a new web design. While the stated hypotheses would be as follow: **1. Null hypothesis:** the old version is as good, or even better than the new version. **2. The alternative hypothesis:** the new version is better than the old version of the website. 

## Conducted Steps:
1. **Assessing and Cleaning the data:** 
* visual and programmatic assessment of the data frame
* the drop of duplicated values
* match control, meaning checking if the user's group (control vs. treatment) matches the assigned web design (old vs. new)
2. **Probability Testing:** 
* calculating the general conversion rate, as well as, conversions rates per group: control versus treatment
* formulating conclusion regarding which of the two web designs would satisfy the company's needs better 
3. **A/B Testing:**
* creating a for loop of 10,000 repetitions, using bootstrapping to simulate new data sampling, and to calculate differences in conversions rates between the control and treatment groups
* plotting a histogram of obtained differences
plotting a histogram under the null distribution
calculating the p-value
* for comparison calculating the test statistics and p-value using the built-in function of statsmodels: stats.proportions_ztest
* formulating the conclusions regarding page suitability 

4. **Linear approach:**
* creating dummy variables
* using statsmodels fitting multiple logistic regressions of conversion rates 
* formulating conclusions for each model regarding its conversion rates and investigated parameters 


