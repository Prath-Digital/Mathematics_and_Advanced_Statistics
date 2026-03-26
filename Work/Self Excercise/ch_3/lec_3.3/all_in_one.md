# Self Exercise - 3.3

---

## Q1. What is a one-sample z-test?
**Answer:**  
A one-sample z-test is a statistical test used to determine whether the mean of a sample is significantly different from a known or hypothesized population mean when the population standard deviation is known and the sample size is large (n ≥ 30).

---

## Q2. When is it appropriate to use a one-sample z-test?
**Answer:**  
It is appropriate when:
- Population standard deviation (σ) is known.
- Sample size is large (n ≥ 30).
- Data is approximately normally distributed (or n is large enough for CLT).
- Observations are independent.

---

## Q3. What are the key assumptions of a one-sample z-test?
**Answer:**
1. Random sampling.
2. Independence of observations.
3. Known population standard deviation.
4. Normal distribution (or large sample size).

---

## Q4. Write the formula for z-statistic in a one-sample z-test.
**Answer:**

$$
z = \frac{\bar{x} - \mu_0}{\sigma / \sqrt{n}}
$$

#### Where:

- $\bar{x}$ = Sample mean  
- $\mu_0$ = Hypothesized population mean (under $H_0$)  
- $\sigma$ = Known population standard deviation  
- $n$ = Sample size  
- $\sigma / \sqrt{n}$ = Standard Error of the Mean (SEM)

---

## Q5. A company claims their average delivery time is 3 days. You collected a sample and found an average of 2.6 days with a known standard deviation. How would you test this claim using a one-sample z-test?
**Answer:**

### Step 1: State hypotheses  
- H₀: μ = 3  
- H₁: μ ≠ 3  

### Step 2: Compute z-statistic  
Use:  
z = (2.6 − 3) / (σ / √n)

### Step 3: Compare with critical value  
At α = 0.05 (two-tailed), critical values = ±1.96.

### Step 4: Conclusion  
If |z| > 1.96 → Reject H₀.  
Otherwise → Fail to reject H₀.

---

## Q6. What is the null hypothesis in a one-sample z-test?
**Answer:**  
The null hypothesis (H₀) states that the population mean is equal to a specified value.

---

## Q7. What is the p-value, and how is it interpreted?
**Answer:**  
The p-value is the probability of obtaining a result as extreme as the observed result assuming H₀ is true.  
- If p ≤ α → Reject H₀  
- If p > α → Fail to reject H₀  

---

## Q8. What is a two-sample z-test?
**Answer:**  
A two-sample z-test compares the means of two independent samples when both population standard deviations are known.

---

## Q9. When do we use a two-sample z-test instead of a t-test?
**Answer:**  
Use a two-sample z-test when:
- Both population standard deviations are known.
- Sample sizes are large.
Otherwise, use a t-test.

---

## Q10. What assumptions must be satisfied for a two-sample z-test?
**Answer:**
1. Independent samples.
2. Known population standard deviations.
3. Normal distribution (or large samples).
4. Random sampling.

---

## Q11. Write the formula for z-statistic in a two-sample z-test.
**Answer:**

\\[
z = \\frac{\\bar{x}_1 - \\bar{x}_2}{\\sqrt{\\frac{\\sigma_1^2}{n_1} + \\frac{\\sigma_2^2}{n_2}}}
\\]

---

## Q12. Two factories produce lightbulbs. You want to test if their average lifespans are significantly different. How would you apply a two-sample z-test?
**Answer:**

### Step 1: State hypotheses  
- H₀: μ₁ = μ₂  
- H₁: μ₁ ≠ μ₂  

### Step 2: Calculate z using formula above.

### Step 3: Compare with critical value or p-value.

### Step 4: Make decision based on α level.

---

## Q13. How do you formulate null and alternative hypotheses in a two-sample z-test?
**Answer:**
- H₀: μ₁ − μ₂ = 0  
- H₁: μ₁ − μ₂ ≠ 0 (two-tailed)  
- Or use > or < for one-tailed tests.

---

## Q14. What does it mean if the z-statistic is greater than the critical value?
**Answer:**  
It means the result is statistically significant, and we reject the null hypothesis.

---

## Q15. What is the difference between pooled variance and known population variance in z-tests?
**Answer:**  
- Known population variance: Used directly in z-test when σ is known.  
- Pooled variance: Used in t-tests when population variances are unknown but assumed equal.

---
