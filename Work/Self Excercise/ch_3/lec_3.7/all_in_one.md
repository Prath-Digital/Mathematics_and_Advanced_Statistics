# 📘 Self-Exercise - #3.7

------------------------------------------------------------------------

## Q1. Define covariance. What does a positive and negative covariance indicate about the relationship between two variables?

**Answer:**\
Covariance measures the direction of the relationship between two
variables.

-   **Positive covariance** → Both variables move in the same
    direction.\
-   **Negative covariance** → Variables move in opposite directions.

------------------------------------------------------------------------

## Q2. Differentiate between covariance and correlation. Why is correlation preferred in data analysis?

**Answer:**

  Feature          Covariance                    Correlation
  ---------------- ----------------------------- ----------------------
  Measure          Direction of relationship     Strength + Direction
  Range            (-∞ to +∞)                    -1 to +1
  Unit             Depends on data units         Unit-free
  Interpretation   Hard to interpret magnitude   Easy to interpret

**Correlation is preferred** because it is standardized and easier to
interpret.

------------------------------------------------------------------------

## Q3. Write a Python function to calculate the covariance between two lists of data points.

``` python
import numpy as np

def calculate_covariance(x, y):
    return np.cov(x, y)[0][1]
```

------------------------------------------------------------------------

## Q4. Calculate the covariance for the following datasets:

X = \[2, 4, 6, -8\]\
Y = \[1, 3, 2, 5\]

**Step 1: Compute means**\
Mean(X) = 1\
Mean(Y) = 2.75

**Step 2: Apply covariance formula**

Cov(X,Y) = Σ\[(Xi - X̄)(Yi - Ȳ)\] / (n-1)

**Final Answer:**\
Covariance ≈ **-5.67**

------------------------------------------------------------------------

## Q5. What is the Pearson correlation coefficient? Explain its range and meaning.

**Answer:**\
Pearson correlation measures the linear relationship between two
variables.

Range: **-1 to +1**

-   +1 → Perfect positive linear relationship\
-   0 → No linear relationship\
-   -1 → Perfect negative linear relationship

------------------------------------------------------------------------

## Q6. Given two variables A and B with a Pearson correlation coefficient of -0.95, interpret the relationship.

**Answer:**\
There is a **very strong negative linear relationship** between A and
B.\
As A increases, B almost perfectly decreases.

------------------------------------------------------------------------

## Q7. Calculate the Pearson correlation coefficient in Python using scipy.stats.

``` python
from scipy.stats import pearsonr

x = [2, 4, 6, -8]
y = [1, 3, 2, 5]

corr, _ = pearsonr(x, y)
print(corr)
```

------------------------------------------------------------------------

## Q8. Explain when to use Spearman correlation instead of Pearson correlation.

**Answer:**\
Use Spearman correlation when:

-   Data is not normally distributed\
-   Relationship is monotonic but not linear\
-   Data is ordinal or ranked\
-   Outliers are present

------------------------------------------------------------------------

## Q9. What type of data is suitable for Spearman correlation? Give an example scenario.

**Answer:**\
Spearman is suitable for **ordinal or ranked data**.

Example:\
Ranking students based on marks vs ranking based on attendance.

------------------------------------------------------------------------

## Q10. Rank the values and calculate the Spearman rank correlation manually:

X = \[20, 18, 22, 20\]\
Y = \[60, 65, 58, 62\]

**Step 1: Assign ranks (average for ties)**

X ranks → \[2.5, 1, 4, 2.5\]\
Y ranks → \[2, 4, 1, 3\]

**Step 2: Use Spearman formula**

ρ = 1 - (6 Σd²) / (n(n² - 1))

**Final Answer:**\
Spearman correlation ≈ **-0.2** (weak negative relationship)

------------------------------------------------------------------------

## Q11. What does a Spearman correlation of 1, -1, and 0 indicate?

**Answer:**

-   1 → Perfect increasing monotonic relationship\
-   -1 → Perfect decreasing monotonic relationship\
-   0 → No monotonic relationship

------------------------------------------------------------------------

## Q12. Write a Python example that compares Pearson and Spearman correlation results.

``` python
from scipy.stats import pearsonr, spearmanr

x = [10, 20, 30, 40, 50]
y = [5, 15, 25, 35, 60]

pearson_corr, _ = pearsonr(x, y)
spearman_corr, _ = spearmanr(x, y)

print("Pearson:", pearson_corr)
print("Spearman:", spearman_corr)
```

------------------------------------------------------------------------

✨ End of Document
