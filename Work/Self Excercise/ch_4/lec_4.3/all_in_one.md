# Self Exercise - 4.3

---

## Q1. What is a Poisson distribution?

**Answer:**  
A Poisson distribution is a discrete probability distribution that models the number of events occurring in a fixed interval of time or space, given that:
- Events occur independently
- The average rate (λ) is constant

Probability formula:

P(X = k) = (e^(-λ) * λ^k) / k!

---

## Q2. State two conditions where the Poisson distribution is applicable.

**Answer:**  
1. Events occur independently of each other.  
2. The average rate (λ) of occurrence remains constant over the interval.

---

## Q3. What are the mean and variance of a Poisson distribution?

**Answer:**  
For a Poisson distribution:

Mean = λ  
Variance = λ  

Both mean and variance are equal.

---

## Q4. Give a real-life example where a Poisson distribution can be used.

**Answer:**  
- Number of customer arrivals at a store per hour.  
- Number of emails received per minute.

---

## Q5. What is a Z-score in probability and statistics?

**Answer:**  
A Z-score measures how many standard deviations a data point is from the mean.

Formula:

Z = (X - μ) / σ

---

## Q6. How does a Z-score help in comparing data across different distributions?

**Answer:**  
Z-scores standardize values, allowing comparison between datasets with different means and standard deviations by converting them into a common scale.

---

## Q7. What does a positive and negative Z-score indicate?

**Answer:**  
- Positive Z-score → Value is above the mean  
- Negative Z-score → Value is below the mean  
- Z = 0 → Value equals the mean

---

## Q8. What is the Probability Density Function (PDF)?

**Answer:**  
A Probability Density Function describes the likelihood of a continuous random variable taking on a specific value.

The total area under the PDF curve equals 1.

---

## Q9. What does the area under a Probability Density Function curve represent?

**Answer:**  
The area under the curve between two points represents the probability that the variable falls within that interval.

---

## Q10. Define the Cumulative Distribution Function (CDF).

**Answer:**  
The CDF gives the probability that a random variable X is less than or equal to a specific value x.

F(x) = P(X ≤ x)

---

## Q11. How is the CDF related to the PDF?

**Answer:**  
The CDF is the integral of the PDF.

F(x) = ∫ f(t) dt  

The PDF is the derivative of the CDF.

---

## Q12. Give an example of how the CDF is used in decision-making in statistics.

**Answer:**  
In hypothesis testing, the CDF is used to determine p-values.  
For example, using the normal CDF to calculate the probability of observing a test statistic under the null hypothesis.