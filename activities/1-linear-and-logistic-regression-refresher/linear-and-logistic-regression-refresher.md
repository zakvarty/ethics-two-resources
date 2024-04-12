# Refresher: Linear and Logistic Regression 

Much of the technical material from this week you have met already, in terms of implementing and interpreting linear and logistic regressions.

## Exercise 1

To refresh your knowledge, you may want to review the relevant lab exercises on multiple linear regression and logistic regression from the supervised learning course.

We suggest that for at least one example of linear regression and one example of logistic regression you fit a model by forward selection. For each intermediate model during the forward selection procedure, interpret the estimated model coefficients for a non-specialist.

## Exercise 2

As an optional second exercise, you may want to implement the same exercises but using python.

To help you with this you might like to reference:

- The [sklearn module help pages](https://scikit-learn.org/stable/index.html). sklearn provides a wide range of machine learning model implementations, which are analogous to those you met in R during the supervised learning course. You have even seen a few of these already in the first part of this course. The SciPy output is mainly focused on point estiamation and so is more limited than you may now be used to. You may want to focus on the help pages for [linear regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html) and [logistic regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html).

- The [StatsModels module help pages](https://www.statsmodels.org/stable/index.html). The StatsModels module gives uncertainty-focused implementations of many machine learning models. The resulting output in more comprehensive in its treatment of parameter and model uncertainties. You may want to focus on the help pages for [linear regression](https://www.statsmodels.org/stable/examples/notebooks/generated/ols.html) and [logistic regression](https://www.statsmodels.org/stable/generated/statsmodels.discrete.discrete_model.Logit.html?highlight=logit#statsmodels.discrete.discrete_model.Logit). (see also the [generalised linear models](https://www.statsmodels.org/stable/glm.html) page)

- This [git repo](https://github.com/emredjan/ISL-python), in which the Introduction to Statistical Learning with R labs have been reproduced in python. There is now a version of the book in Python too, you can download the full pdf for free from [https://www.statlearning.com/](https://www.statlearning.com/). 