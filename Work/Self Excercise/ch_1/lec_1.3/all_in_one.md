# Self Exercise - 1.3

---

## Q1. What is a Gaussian (Normal) Distribution in statistics?
**Answer:**  
A Gaussian or Normal Distribution is a continuous probability distribution that is symmetric around its mean. Most data points cluster around the mean, and the probabilities taper off equally on both sides, forming a bell-shaped curve.

---

## Q2. What are the key characteristics of a normal distribution curve?
**Answer:**  
- Bell-shaped and symmetric  
- Mean = Median = Mode  
- Total area under the curve equals 1  
- Defined by mean (μ) and standard deviation (σ)  
- Follows the Empirical Rule (68–95–99.7)

---

## Q3. Why is the normal distribution important in data analysis and machine learning?
**Answer:**  
- Many natural phenomena follow it  
- Assumption for many statistical tests  
- Simplifies modeling and inference  
- Improves performance of ML algorithms  
- Helps in probability estimation

---

## Q4. What is a percentile, and how is it used in data interpretation?
**Answer:**  
A percentile indicates the value below which a given percentage of observations fall.  
Example: 90th percentile means 90% of values are below it.

---

## Q5. Define quartiles. How are Q1, Q2, and Q3 calculated?
**Answer:**  
Quartiles divide data into four equal parts:
- Q1 (25th percentile)  
- Q2 (50th percentile / Median)  
- Q3 (75th percentile)

---

## Q6. What is the Interquartile Range (IQR), and what does it represent?
**Answer:**  
IQR = Q3 − Q1  
It measures the spread of the middle 50% of the data and is resistant to outliers.

---

## Q7. What are the components of a Five Number Summary?
**Answer:**  
- Minimum  
- Q1  
- Median (Q2)  
- Q3  
- Maximum  

---

## Q8. Explain how a boxplot represents a dataset using the five-number summary.
**Answer:**  
- Box spans from Q1 to Q3  
- Line inside box shows the median  
- Whiskers extend to min and max (excluding outliers)

---

## Q9. How does a boxplot help in identifying outliers?
**Answer:**  
Values beyond 1.5 × IQR from Q1 or Q3 are marked as outliers.

---

## Q10. What is skewness in a distribution?
**Answer:**  
Skewness measures the asymmetry of a distribution.

---

## Q11. What does it mean if a dataset is positively skewed?
**Answer:**  
The right tail is longer.  
Mean > Median > Mode.

---

## Q12. What does it mean if a dataset is negatively skewed?
**Answer:**  
The left tail is longer.  
Mean < Median < Mode.

---

## Q13. How can skewness affect the mean, median, and mode?
**Answer:**  
- Positive skew: Mean pulled right  
- Negative skew: Mean pulled left  
- Median is more robust

---

## Q14. Why is it important to detect and fix skewness in data science?
**Answer:**  
- Improves model assumptions  
- Enhances statistical validity  
- Boosts ML performance  

---

## Q15. What is kurtosis in a distribution?
**Answer:**  
Kurtosis measures the heaviness of tails and presence of outliers.

---

## Q16. What are the three types of kurtosis?
**Answer:**  
- Leptokurtic: Heavy tails  
- Mesokurtic: Normal-like  
- Platykurtic: Light tails  

---

## Q17. How does kurtosis help in understanding tails and outliers?
**Answer:**  
Higher kurtosis indicates more extreme values and higher outlier risk.

---

## Q18. Why is kurtosis often compared with 3 in its calculation?
**Answer:**  
Because a normal distribution has kurtosis = 3.  
Excess kurtosis = Kurtosis − 3.