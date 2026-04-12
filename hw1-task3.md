# Homework 1 Task 3

---

Answer the following questions based on exercises from *An Introduction to Statistical Learning with Applications in Python*.

## Chapter 2.4 Exercises

---

### Exercise 1 (ISLP exercise 2)

Explain whether each scenario is a **classification or regression** problem, and indicate whether we are most interested in **inference or prediction**. Finally, provide **n** (size of observation dataset) and **p** (number of predictors).

**(a)**  We collect data on 200 protected marine reserves worldwide. For each reserve we record species richness, reserve size, years since establishment, enforcement budget, and proximity to human settlements. We are interested in understanding which factors affect species richness.

regression (continuous outcome), inference, n = 200, p = 4

---

**(b)** A conservation agency wants to know whether a proposed habitat corridor will successfully support wildlife movement or fail to do so. They collect data on 30 previously established corridors. For each corridor they have recorded whether wildlife movement was successful or unsuccessful, corridor width, length, surrounding land use type, and eight other variables.

classification (binary outcome), prediction, n= 30, p = 11

---

**(c)** We are interested in predicting weekly average ground-level ozone concentration in a coastal city. We collect weekly data for all of 2019. For each week we record average ozone concentration, sea surface temperature, wind speed, solar radiation, and atmospheric

regression (continuous outcome), prediction, n = 52, p = 4

---

### Exercise 2 (ISLP exercise 5)

What are the advantages and disadvantages of a very flexible (versus a a less flexible) approach for regression? Under what circumstances might a more flexible approach be preferred to a less flexible approach? When might a less flexible approach be preferred?

Advantages of a very flexible regression approach is a highly sensitive model, which could be prederable for highly variable data or if inference is not the goal of the model. Disadvantages of a very flexible approach is high variance, which would not be ideal in the case that we are worried about overfitting where a less flexible approach might be better. A less flexible approach would be prefferable when the number of data are small relative to predictors.
---

### Exercise 3 (ISLP exercise 6)

Describe the differences between a **parametric** and a **non-parametric** statistical learning approach. What are the **advantages** of a parametric approach to regression or classification (as opposed to a non-parametric approach)? What are its **disadvantages**?

A parametric approach assumes a given relationship in the model already, where a nonparametric approach does not have a set function. 
A parametric approach is helpful for smaller normally distributed datasets, where non-parametric approaches can help with high variance or skewness, a lot of outliers, or large datasets. Parametric approaches are helpful when you know your fixed paramaters, but this is problematic if this does not include all actual predictors. Non-parametric approaches are a lot more flexible but need more data for accuracy and are harder to interpet.