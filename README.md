# Bayesian-methods-for-classification


**Aim:**

Implement Bayesian methods for classification

**Theory:**

Bayesian classification is based on Bayes' Theorem. Bayesian classifiers are the statistical classifiers. Bayesian classifiers can predict class membership probabilities such as the probability that a given tuple belongs to a particular class.
Let’s take a look at the Baye’s Formula

![image](https://github.com/AdityaPatil0718/Bayesian-methods-for-classification/assets/128233555/1046c338-2c4b-4d20-989a-be6f49ab4e01)
 
P(X/w) is the likelihood probability of occurring X given that event w has occurred.
P(w) is the prior probability of event w,
P(X) is the marginal probability of event X occurring, marginal probability refers to the likelihood of the particular event happening without considering any other events. It focuses on the individual probability of a single event.
P(w/X) is the posterior probability, representing the updated probability of event w happening given that event X has occurred.
To understand how the Bayes formula is derived, see the conditional probability

![image](https://github.com/AdityaPatil0718/Bayesian-methods-for-classification/assets/128233555/3ba592f8-621b-4083-966c-f2aeab06c342)

And we know that P(w union X) = P(X union w). Therefore,

![image](https://github.com/AdityaPatil0718/Bayesian-methods-for-classification/assets/128233555/a8c87cfb-58f2-4b2c-9a80-ffdee3577722)
 
hence Bayes theorem is derived!


**Conclusion:**

Bayesian methods for classification, such as Naive Bayes, offer a simple yet effective approach for modeling the class conditional densities and making predictions based on Bayes' theorem.

