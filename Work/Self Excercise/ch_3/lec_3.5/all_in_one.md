# Self Exercise - 3.5

## Q1. What is the Central Limit Theorem (CLT) in simple words?

The Central Limit Theorem states that when we take sufficiently large
random samples from any population, the distribution of the sample means
will be approximately normal, regardless of the population's original
distribution.

------------------------------------------------------------------------

## Q2. Why is CLT important in statistics and data science?

-   It allows us to use normal distribution methods even when the
    population is not normal.
-   It forms the foundation for confidence intervals and hypothesis
    testing.
-   It simplifies probability calculations for sample means.

------------------------------------------------------------------------

## Q3. State the assumptions under which the CLT applies.

1.  Samples are randomly selected.
2.  Observations are independent.
3.  Sample size is sufficiently large (commonly n ≥ 30).
4.  Population has finite variance.

------------------------------------------------------------------------

## Q4. How does the sample size affect the shape of the sampling distribution?

As sample size increases: - The sampling distribution becomes more
normal. - Skewness decreases. - Approximation improves.

------------------------------------------------------------------------

## Q5. What happens to the mean and standard deviation of the sampling distribution according to CLT?

-   Mean of sampling distribution = population mean (μ).
-   Standard deviation = σ / √n (called standard error).

------------------------------------------------------------------------

## Q6. Explain how CLT is used in constructing confidence intervals.

Since the sampling distribution of the mean becomes approximately normal
for large samples, we can use:

Confidence Interval = x̄ ± Z \* (σ / √n)

or

Confidence Interval = x̄ ± t \* (s / √n)

depending on whether population standard deviation is known.

------------------------------------------------------------------------

## Q7. Can CLT be applied to non-normally distributed populations? If yes, under what condition?

Yes. If the sample size is large enough (typically n ≥ 30), the sampling
distribution of the mean will be approximately normal.

------------------------------------------------------------------------

## Q8. Why is CLT important in performing hypothesis testing?

CLT justifies using Z-tests and t-tests because it ensures the sampling
distribution of the mean is approximately normal.

------------------------------------------------------------------------

## Q9. What is a Chi-Square Test and when is it used?

A Chi-Square test is a statistical test used to determine whether there
is a significant association between categorical variables or whether
observed frequencies differ from expected frequencies.

------------------------------------------------------------------------

## Q10. Differentiate between:

### Chi-Square Goodness-of-Fit Test:

-   Tests whether observed data fits a specified distribution.
-   Example: Checking if dice outcomes are equally likely.

### Chi-Square Test of Independence:

-   Tests whether two categorical variables are related.
-   Example: Gender vs Job Preference.

------------------------------------------------------------------------

## Q11. What are the assumptions for using a Chi-Square test?

1.  Data is categorical.
2.  Observations are independent.
3.  Expected frequency in each cell should be at least 5.
4.  Random sampling.

------------------------------------------------------------------------

## Q12. What type of data is suitable for a Chi-Square test?

Categorical data (nominal or ordinal) presented as frequency counts.

------------------------------------------------------------------------

## Q13. Define observed frequencies and expected frequencies in a Chi-Square context.

-   Observed frequency (O): Actual count from collected data.
-   Expected frequency (E): Theoretical count assuming null hypothesis
    is true.

------------------------------------------------------------------------

## Q14. What is the formula for the Chi-Square statistic?

χ² = Σ \[(O - E)² / E\]

Where: - O = Observed frequency - E = Expected frequency

------------------------------------------------------------------------

## Q15. A company wants to know if gender and job preference are related. Which type of Chi-Square test should be applied?

Chi-Square Test of Independence.

------------------------------------------------------------------------

## Q16. What is the role of degrees of freedom in a Chi-Square test?

Degrees of freedom determine the shape of the Chi-Square distribution
and are calculated as:

df = (rows - 1) × (columns - 1)

------------------------------------------------------------------------

## Q17. What does a p-value \< 0.05 indicate in a Chi-Square test result?

If p \< 0.05: - Reject the null hypothesis. - Conclude there is a
statistically significant association between variables.
