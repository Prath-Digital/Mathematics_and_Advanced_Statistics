# Self Exercise - 2.4

---

## Q1. What is conditional probability?

**Answer:**  
Conditional probability is the probability of an event occurring **given that another event has already occurred**. It updates the likelihood of an event based on new information.

---

## Q2. Explain the real-life significance of conditional probability.

**Answer:**  
Conditional probability helps us make better decisions when partial information is available.  
Examples include:
- Predicting rain given cloudy weather  
- Medical diagnosis based on test results  
- Machine learning models updating predictions with new data  

---

## Q3. State the formula for conditional probability and define each term.

**Answer:**  

\\[
P(A \\mid B) = \\frac{P(A \\cap B)}{P(B)}
\\]

Where:
- \\( P(A \\mid B) \\) = Probability of event A given event B  
- \\( P(A \\cap B) \\) = Probability that both A and B occur  
- \\( P(B) \\) = Probability of event B  

---

## Q4. Give an intuitive explanation of the conditional probability formula.

**Answer:**  
Conditional probability **narrows down the sample space**.  
Once event B happens, we only consider outcomes where B occurs, and from those, we find how often A also occurs.

---

## Q5. How can conditional probability be visualized using a Venn diagram?

**Answer:**  
In a Venn diagram:
- The overlap of circles A and B represents \\( A \\cap B \\)
- Conditional probability focuses only on the B circle
- The ratio of overlap to total area of B gives \\( P(A \\mid B) \\)

---

## Q6. Define independent events in probability.

**Answer:**  
Two events are **independent** if the occurrence of one **does not affect** the probability of the other.

Mathematically:
\\[
P(A \\mid B) = P(A)
\\]

---

## Q7. Define dependent events in probability.

**Answer:**  
Events are **dependent** if the occurrence of one **changes the probability** of the other.

Example:  
Drawing cards from a deck **without replacement**.

---

## Q8. What are mutually exclusive events? Give an example.

**Answer:**  
Mutually exclusive events **cannot occur at the same time**.

Example:
- Getting heads or tails in a single coin toss

\\[
P(A \\cap B) = 0
\\]

---

## Q9. How do mutually exclusive events differ from independent events?

**Answer:**  

| Mutually Exclusive | Independent |
|-------------------|------------|
| Cannot occur together | Can occur together |
| \\( P(A \\cap B) = 0 \\) | \\( P(A \\cap B) = P(A)P(B) \\) |
| Dependent by nature | No effect on each other |

---

## Q10. What is Bayes' theorem in probability?

**Answer:**  
Bayes' theorem describes how to **update probabilities** when new evidence is available.

\\[
P(A \\mid B) = \\frac{P(B \\mid A)P(A)}{P(B)}
\\]

---

## Q11. Explain the intuition behind Bayes' theorem.

**Answer:**  
Bayes' theorem:
- Starts with a **prior belief**
- Incorporates **new evidence**
- Produces an updated **posterior probability**

It is learning from experience using probability.

---

## Q12. Mention at least two real-world applications of Bayes' theorem.

**Answer:**  
1. Medical diagnosis (disease prediction from test results)  
2. Spam email filtering  
3. Fraud detection  
4. Machine learning & AI models  

---