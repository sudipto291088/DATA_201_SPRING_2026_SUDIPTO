# DATA 201 — Week 5 Assignment
## Resampling Methods with the Iris Dataset

This assignment explores three resampling techniques using the Iris dataset.

The dataset contains 150 flower observations from three species:
Setosa, Versicolor, and Virginica. Each flower includes measurements of
sepal length, sepal width, petal length, and petal width.

----------------------------------

Part 1 — Bootstrap Resampling

Bootstrap resampling was used to estimate the mean sepal length.

Steps performed:
- Calculated mean, median, and standard deviation of sepal length
- Generated 5,000 bootstrap samples
- Computed the mean sepal length for each resample
- Stored the bootstrap means
- Plotted the distribution of bootstrap means
- Constructed a 95% confidence interval using the percentile method

----------------------------------

Part 2 — Jackknife Resampling

Jackknife resampling was used to examine how sensitive the mean is to
individual observations.

Steps performed:
- Removed one observation at a time
- Calculated the mean of the remaining observations
- Stored each jackknife mean
- Generated 150 jackknife samples
- Plotted the distribution of jackknife means

----------------------------------

Part 3 — Permutation Test

A permutation test was performed to determine whether sepal length differs
between Versicolor and Virginica.

Steps performed:
- Computed the observed difference in means
- Ran 1,000 permutations
- Randomly shuffled species labels
- Recomputed the difference in means for each permutation
- Plotted the permutation distribution
- Calculated the p-value

----------------------------------

Conclusion

The p-value was less than 0.05, so we reject the null hypothesis.
This suggests that the average sepal length between Versicolor and
Virginica flowers is significantly different.

----------------------------------

Key Concepts

Bootstrap Resampling
Jackknife Resampling
Permutation Testing
Confidence Intervals
Hypothesis Testing
