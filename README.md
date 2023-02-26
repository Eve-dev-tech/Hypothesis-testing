# Hypothesis-testing
Hypothesis Test for Population Mean
### One Sample Z-test (when population standard deviation is known)

It is rarely the case when you know the population standard deviation and not the mean but let's assume that is the case.

It is known from experience that for a certain E-commerce company the mean delivery time of the products is 5 days with a standard deviation of 1.3 days.

The new customer service manager of the company is afraid that the company is slipping and collects a random sample of 45 orders. The mean delivery time of these samples comes out to be 5.25 days. 

Is there enough statistical evidence for the manager’s apprehension that the mean delivery time of products is greater than 5 days?

Use level of significance $\alpha$ = 0.05.

### Let's write the null hypothesis and alternate hypothesis

Let $\mu$ be the mean delivery time of the products.

The manager will test the null hypothesis

>$H_0: \mu = 5$

against the alternate hypothesis

> $H_a: \mu > 5$

### Are the assumptions of the Z-test satisfied?


* Samples are drawn from a normal distribution - Since the sample size is 45(which is > 30), Central Limit Theorem states that the distribution of sample means will be normal. If the sample size was less than 30, we would have been able to apply the z test if we knew that the population distribution was normal.  
* Observations are from a simple random sample - we are informed that the manager collected a simple random sample.
* Standard deviation is known - Yes.


Voila! We can use Z-test for this problem.
