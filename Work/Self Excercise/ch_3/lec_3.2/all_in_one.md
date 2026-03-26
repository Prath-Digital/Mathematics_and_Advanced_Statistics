# Self Exercise - 3.2

---

## Q1. Define p-value in your own words and explain its basic interpretation.

**Answer:**\
A p-value is the probability of observing results as extreme as (or more
extreme than) the sample results, assuming the null hypothesis is true.

**Interpretation:**\
- A small p-value means the observed data is unlikely under the null
hypothesis.\
- A large p-value means the data is consistent with the null
hypothesis.\
- If p-value ≤ α (significance level), we reject the null hypothesis.

---

## Q2. Why is a small p-value considered evidence against the null hypothesis?

**Answer:**\
A small p-value indicates that the observed result would be very
unlikely if the null hypothesis were true. Therefore, we consider the
null hypothesis unlikely and reject it.

---

## Q3. Explain how a p-value helps in making decisions during hypothesis testing.

**Answer:**\
1. Choose a significance level (α), such as 0.05.\
2. Calculate the p-value from the data.\
3. Compare p-value with α:\
- If p ≤ α → Reject H₀\
- If p \> α → Fail to reject H₀

This provides a clear decision rule.

---

## Q4. What is a confidence interval? Explain its purpose in statistics.

**Answer:**\
A confidence interval (CI) is a range of values that likely contains the
true population parameter, calculated from sample data.

**Purpose:**\
- Provides an estimate with uncertainty.\
- Shows both precision and reliability of the estimate.\
- Helps in decision-making without relying only on p-values.

---

## Q5. Give one example showing how a confidence interval is used in real-life decision-making.

**Answer:**\
A company estimates average customer spending is ₹500 with a 95% CI of
₹450 to ₹550.\
This means they are 95% confident the true average lies in this range.\
They can use this range for budgeting and forecasting revenue.

---

## Q6. What is meant by the term "critical value" in hypothesis testing?

**Answer:**\
A critical value is the cutoff point that separates the rejection region
from the non-rejection region based on the chosen significance level
(α).

---

## Q7. How is the critical value related to the significance level (α)?

**Answer:**\
The critical value is determined using α.\
For example:\
- If α = 0.05 in a two-tailed test, 0.025 is placed in each tail.\
- The corresponding z-value (±1.96) becomes the critical value.

---

## Q8. Explain how the rejection region is determined using a critical value.

**Answer:**\
1. Select α.\
2. Find the corresponding critical value.\
3. Any test statistic beyond the critical value lies in the rejection
region.\
If the test statistic falls there, reject H₀.

---

## Q9. Describe the difference between one-tailed and two-tailed critical regions.

**Answer:**

**One-tailed test:**\
- Entire α is placed in one tail.\
- Tests for direction (greater than or less than).

**Two-tailed test:**\
- α is divided equally between both tails.\
- Tests for any difference (not equal).

---

## Q10. Give an example showing how a critical value helps in drawing conclusions.

**Answer:**\
Suppose α = 0.05 and the critical z-value is 1.96 (two-tailed).\
If calculated z = 2.5:\
Since 2.5 \> 1.96, it falls in the rejection region.\
Therefore, we reject H₀.

---

## Q11. Define Type I Error and explain what it means in practical terms.

**Answer:**\
A Type I Error occurs when we reject a true null hypothesis.

**Practical meaning:**\
It is a false positive.\
Example: Concluding a medicine works when it actually does not.

---

## Q12. Define Type II Error and give a simple real-world example.

**Answer:**\
A Type II Error occurs when we fail to reject a false null hypothesis.

**Example:**\
Concluding a medicine does not work when it actually does.

---

## Q13. How does reducing the significance level (α) affect Type I and Type II errors?

**Answer:**\
- Lower α reduces the chance of Type I Error.\
- However, it increases the chance of Type II Error (harder to reject
H₀).

There is a trade-off between the two errors.

---

## Q14. Why is it not possible to minimize both Type I and Type II errors at the same time?

**Answer:**\
Reducing Type I Error requires stricter evidence to reject H₀.\
This makes it more difficult to detect real effects, increasing Type II
Error.\
Thus, minimizing one increases the other unless sample size increases.

---

## Q15. In your own words, explain why understanding both error types is important in hypothesis testing.

**Answer:**\
Understanding both errors helps balance risks in decision-making.\
In medical, legal, and business contexts, the cost of each error
differs.\
Choosing the right α and sample size depends on which error is more
serious in that situation.

---
