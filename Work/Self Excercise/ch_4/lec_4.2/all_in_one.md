# 📘 Self Exercise - 4.2

------------------------------------------------------------------------

## Q1. What is a Log-Normal distribution?

**Answer:**\
A Log-Normal distribution is a continuous probability distribution where
the logarithm of the variable follows a normal distribution.

If Y = ln(X) is normally distributed, then X follows a Log-Normal
distribution.

------------------------------------------------------------------------

## Q2. How is a Log-Normal distribution different from a Normal distribution?

**Answer:**

  Feature          Normal Distribution   Log-Normal Distribution
  ---------------- --------------------- -------------------------
  Shape            Symmetric             Right-skewed
  Range            (-∞ to +∞)            (0 to +∞)
  Mean vs Median   Equal                 Mean \> Median
  Log Transform    Not required          Log becomes normal

------------------------------------------------------------------------

## Q3. Mention two real-life examples where data follows a Log-Normal distribution.

**Answer:**\
1. Income distribution of individuals.\
2. Stock prices over time.

------------------------------------------------------------------------

## Q4. What is meant by a Power Law distribution?

**Answer:**\
A Power Law distribution describes a relationship where one quantity
varies as a power of another.

It has the form:\
P(X = x) ∝ x\^(-α)

where α \> 1 is the exponent.

------------------------------------------------------------------------

## Q5. How does the Power Law distribution explain the "80/20 rule" (Pareto principle)?

**Answer:**\
In many systems, a small percentage of causes contribute to a large
percentage of effects.

Example:\
- 20% of customers generate 80% of revenue.\
- 20% of people hold 80% of wealth.

This imbalance is characteristic of power-law behavior.

------------------------------------------------------------------------

## Q6. State two real-world phenomena that can be modeled using a Power Law distribution.

**Answer:**\
1. Earthquake magnitudes.\
2. Social media followers count.

------------------------------------------------------------------------

## Q7. What are the key characteristics of a Power Law distribution?

**Answer:**\
- Heavy tail\
- Scale invariance\
- Few large events, many small events\
- No characteristic scale

------------------------------------------------------------------------

## Q8. What is the Box-Cox transformation?

**Answer:**\
The Box-Cox transformation is a power transformation used to make data
more normally distributed and stabilize variance.

Formula:

For λ ≠ 0:\
Y(λ) = (X\^λ - 1) / λ

For λ = 0:\
Y(λ) = ln(X)

------------------------------------------------------------------------

## Q9. Why is the Box-Cox transform applied to data before statistical modeling?

**Answer:**\
- To reduce skewness\
- To stabilize variance\
- To improve normality\
- To meet regression assumptions

------------------------------------------------------------------------

## Q10. What is the role of the parameter λ (lambda) in the Box-Cox transformation?

**Answer:**\
Lambda controls the type of transformation applied:

-   λ = 1 → No transformation\
-   λ = 0 → Log transformation\
-   λ = 0.5 → Square root transformation\
-   λ = -1 → Reciprocal transformation

------------------------------------------------------------------------

## Q11. How does Box-Cox transformation help in stabilizing variance?

**Answer:**\
It reduces heteroscedasticity (non-constant variance) by compressing
large values and spreading smaller values, making variance more uniform
across data.

------------------------------------------------------------------------

## Q12. Give an example of a scenario where Box-Cox transformation is useful.

**Answer:**\
In regression modeling of house prices, if prices are highly skewed,
applying a Box-Cox (or log) transformation can improve model accuracy
and satisfy linear regression assumptions.

------------------------------------------------------------------------

✨ End of Document
