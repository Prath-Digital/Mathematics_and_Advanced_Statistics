# Self Exercise - 3.6

------------------------------------------------------------------------

## Q1. What does ANOVA stand for? What is the primary purpose of an ANOVA test?

**Answer:**\
ANOVA stands for **Analysis of Variance**.\
Its primary purpose is to determine whether there are statistically
significant differences between the means of three or more groups.

------------------------------------------------------------------------

## Q2. How is ANOVA different from a T-test?

**Answer:**\
- A **T-test** compares the means of **two groups**.\
- **ANOVA** compares the means of **three or more groups**.\
Using multiple t-tests instead of ANOVA increases the risk of Type I
error.

------------------------------------------------------------------------

## Q3. List real-world examples where ANOVA could be used.

**Answer:**\
- Comparing test scores across different teaching methods\
- Comparing sales performance across multiple regions\
- Comparing crop yield across different fertilizers\
- Comparing patient recovery time under different treatments

------------------------------------------------------------------------

## Q4. What is the null hypothesis (H₀) in ANOVA?

**Answer:**\
The null hypothesis states that **all group means are equal**.

H₀: μ₁ = μ₂ = μ₃ = ... = μₖ

------------------------------------------------------------------------

## Q5. What is the alternative hypothesis (H₁) in ANOVA?

**Answer:**\
The alternative hypothesis states that **at least one group mean is
different** from the others.

------------------------------------------------------------------------

## Q6. What are the basic assumptions of ANOVA?

**Answer:**\
1. Independence of observations\
2. Normal distribution of data within each group\
3. Homogeneity of variances (equal variances across groups)

------------------------------------------------------------------------

## Q7. Differentiate between One-Way ANOVA and Two-Way ANOVA.

**Answer:**

### One-Way ANOVA

-   One independent variable\
-   Compares means across groups based on one factor

### Two-Way ANOVA

-   Two independent variables\
-   Tests main effects and interaction effects

------------------------------------------------------------------------

## Q8. What is the meaning of "between-group variance" and "within-group variance"?

**Answer:**

-   **Between-group variance:** Variation due to differences between
    group means.\
-   **Within-group variance:** Variation within each group due to random
    error.

------------------------------------------------------------------------

## Q9. Define the F-statistic in the context of ANOVA. What does a large F-value suggest?

**Answer:**

F = (Between-group variance) / (Within-group variance)

A large F-value suggests that group means are significantly different.

------------------------------------------------------------------------

## Q10. What does it mean if the p-value \< 0.05 in an ANOVA result?

**Answer:**\
If p \< 0.05, reject the null hypothesis.\
This means at least one group mean is significantly different.

------------------------------------------------------------------------

## Q11. What are degrees of freedom (df) in ANOVA? How are df_between and df_within calculated?

**Answer:**

-   df_between = k − 1\
-   df_within = N − k

Where:\
k = number of groups\
N = total observations

------------------------------------------------------------------------

## Q12. What action should be taken if ANOVA shows significant results?

**Answer:**\
Perform a **post-hoc test** (such as Tukey's test) to identify which
specific groups differ.

------------------------------------------------------------------------

## Q13. Why is post-hoc testing needed after ANOVA?

**Answer:**\
ANOVA only tells us that at least one group differs.\
Post-hoc tests determine exactly which groups are significantly
different while controlling Type I error.

------------------------------------------------------------------------

## Q14. What is the risk of Type I error when running multiple t-tests instead of ANOVA?

**Answer:**\
Running multiple t-tests increases the probability of falsely rejecting
a true null hypothesis (false positive).\
This inflates the overall Type I error rate.

------------------------------------------------------------------------

## Q15. When should you not use ANOVA?

**Answer:**\
- When comparing only two groups (use t-test instead)\
- When assumptions of normality or equal variance are violated\
- When data is categorical rather than continuous

------------------------------------------------------------------------

# End of Document
