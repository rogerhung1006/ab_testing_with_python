# AB testing with python
## Introduction
An A/B test is an experiment in which you test two different values of the same variable against one another to determine which one is “better” by evaluating their performance among two randomly assigned groups of real users.
In this project, I will focus more on the ab test result analysis. The typical ab testing process is to randomly selecting a subset of users and show them the new feature, and monitor the conversion behavior of this group compared to the other users. We can then observe whether one group converts at a higher rate than the other.
The data I am using for this project is from kaggle. The dataset contains the conversion rates of two groups (control and treatment) exposed to different landing pages. The dataset comprises twenty-nine thousand rows of datapoints.

## Clean the data and check sanity

whether this difference is statistically significant. That is, measuring if the values differ more than would be expected due to randomness. This is where the p-value comes in.

## Calculate the p-value
The p-value is the probability of observing a value as or more extreme than the observed value under the Null hypothesis. If this value is low, then it means either our power is low or there is a low probability of observing this value if the Null hypothesis is true.
It turns out that the we are having a p-value of 0.189, which is larger confidence level of 0.1, suggesting that we cannot reject the Null hypothesis and conclude which landing page drives more conversions.


## Calculate the statistical power
Statistical power is the probability of finding statistically significant results when the Alternative hypothesis is true. They are roughly comparable


## Calculate the confidence intervals


course “A/B Testing by Google offered by Udacity
