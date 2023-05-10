# propensityscore_analysis

In this propensity score analysis, I sought to answer the following question : 
Among adults 18 - 29 years hospitalized in the United States in 2015, what is the effect of health insurance status on the duration of their hospital stay?

To answer the research question above, I conducted a propensity score analysis utilizing machine learning algorithms. Specifically, we examined and compared logistic regression and Lasso to construct the propensity scores. After constructing the propensity score and matching to obtain comparable groups, we assessed their performance by comparing the distributions of covariates between the exposed and unexposed groups. Following this, I created a logistic regression model to examine the effect of insurance status on length of hospital stay using the propensity scores model from the two algorithms described above.
