# Self Exercise - 3.4

## Q1. What is a one-sample t-test?

A one-sample t-test is a statistical test used to determine whether the
mean of a single sample differs significantly from a known or
hypothesized population mean.

------------------------------------------------------------------------

## Q2. When should you use a t-test instead of a z-test?

Use a t-test when: - The population standard deviation is unknown. - The
sample size is small (typically n \< 30). - The data is approximately
normally distributed.

------------------------------------------------------------------------

## Q3. What are the assumptions of a one-sample t-test?

1.  The data is continuous.
2.  The sample is randomly selected.
3.  The data is approximately normally distributed.
4.  Observations are independent.

------------------------------------------------------------------------

## Q4. Write the formula to calculate the t-statistic for a one-sample t-test.

t = (x̄ - μ) / (s / √n)

Where: - x̄ = sample mean\
- μ = population mean\
- s = sample standard deviation\
- n = sample size

------------------------------------------------------------------------

## Q5. A class claims its average test score is 75. A sample of 10 students has a mean of 70. How would you test this using a one-sample t-test?

Step 1: Define hypotheses\
- H0: μ = 75\
- H1: μ ≠ 75

Step 2: Calculate t-statistic using the formula.

Step 3: Find degrees of freedom (df = n - 1 = 9).

Step 4: Compare t-value with critical value or calculate p-value.

Step 5: Make decision based on significance level (e.g., 0.05).

------------------------------------------------------------------------

## Q6. What is the role of degrees of freedom in a one-sample t-test?

Degrees of freedom (df = n - 1) determine the shape of the
t-distribution and affect the critical value used for hypothesis
testing.

------------------------------------------------------------------------

## Q7. How does sample size impact the one-sample t-test?

-   Larger sample size → smaller standard error → more precise estimate.
-   Larger samples make the t-distribution closer to normal
    distribution.

------------------------------------------------------------------------

## Q8. What is a two-sample t-test?

A two-sample t-test compares the means of two independent groups to
determine if there is a statistically significant difference between
them.

------------------------------------------------------------------------

## Q9. Differentiate between independent and paired two-sample t-tests.

### Independent t-test:

-   Compares two unrelated groups.
-   Example: Scores of two different classes.

### Paired t-test:

-   Compares two related measurements.
-   Example: Before and after treatment scores.

------------------------------------------------------------------------

## Q10. What assumptions are made in a two-sample t-test?

1.  Independent observations.
2.  Normally distributed populations.
3.  Equal variances (for pooled t-test).
4.  Random sampling.

------------------------------------------------------------------------

## Q11. Write the formula for the t-statistic in an independent two-sample t-test.

t = (x̄1 - x̄2) / √\[(s1²/n1) + (s2²/n2)\]

Where: - x̄1, x̄2 = sample means\
- s1², s2² = sample variances\
- n1, n2 = sample sizes

------------------------------------------------------------------------

## Q12. Two groups of patients are given different medicines. Their recovery times are recorded. How would you check if there's a significant difference using a two-sample t-test?

Step 1: Define hypotheses\
- H0: μ1 = μ2\
- H1: μ1 ≠ μ2

Step 2: Choose independent t-test.

Step 3: Calculate t-statistic.

Step 4: Determine degrees of freedom.

Step 5: Compare with critical value or compute p-value.

Step 6: Draw conclusion.

------------------------------------------------------------------------

## Q13. How do you define the null and alternative hypotheses for a two-sample t-test?

-   Null Hypothesis (H0): μ1 = μ2\
-   Alternative Hypothesis (H1): μ1 ≠ μ2 (two-tailed)\
    or μ1 \> μ2 / μ1 \< μ2 (one-tailed)

------------------------------------------------------------------------

## Q14. When should you use a pooled variance in a two-sample t-test?

Use pooled variance when: - The two populations are assumed to have
equal variances. - Sample sizes are similar.

------------------------------------------------------------------------

## Q15. What does it mean if the p-value is less than 0.05 in a two-sample t-test?

If p \< 0.05: - Reject the null hypothesis. - Conclude that there is a
statistically significant difference between the two group means.
