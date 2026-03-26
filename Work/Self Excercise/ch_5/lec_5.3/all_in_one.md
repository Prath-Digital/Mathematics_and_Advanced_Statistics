# Self Excercise - 5.3

## Q1. What is the formula to calculate the angle between two vectors?
**Answer:**  
The angle between two vectors a and b is calculated using:  
\\[
\\cos(\\theta) = \\frac{\\vec{a} \\cdot \\vec{b}}{||\\vec{a}|| \\, ||\\vec{b}||}
\\]

---

## Q2. How does the dot product relate to the angle between two vectors?
**Answer:**  
The dot product directly includes the cosine of the angle:  
\\[
a \\cdot b = ||a|| \\, ||b|| \\cos(\\theta)
\\]
where $a \cdot b$ is the dot product, and $||a||$, $||b||$ are the norms (magnitudes) of vectors $a$ and $b$.

It helps determine how aligned two vectors are.

---

## Q3. Explain how the cosine of the angle between vectors helps measure their similarity.
**Answer:**  
- cos(θ) = 1 → vectors are identical (maximum similarity)  
- cos(θ) = 0 → vectors are perpendicular (no similarity)  
- cos(θ) = -1 → vectors are opposite  

This concept is used in cosine similarity in machine learning.

---

## Q4. Define vector projection.
**Answer:**  
Vector projection is the projection of one vector onto another, showing how much one vector lies in the direction of another.

---

## Q5. What is the difference between the scalar projection and vector projection?
**Answer:**  
- Scalar projection: magnitude of projection (a number)  
  - Formula:  
	\\[
	\mathrm{Scalar\ Projection\ of\ } \vec{a} \mathrm{\ on\ } \vec{b} = \frac{\vec{a} \cdot \vec{b}}{||\vec{b}||}
	\\]
- Vector projection: actual projected vector with direction  
  - Formula:  
	\\[
	\mathrm{Vector\ Projection\ of\ } \vec{a} \mathrm{\ on\ } \vec{b} = \left( \frac{\vec{a} \cdot \vec{b}}{||\vec{b}||^2} \right) \vec{b}
	\\]

---

## Q6. Give one practical application of vector projection in physics or machine learning.
**Answer:**  
In physics, vector projection is used to calculate the component of force in a particular direction.  
In machine learning, it is used in dimensionality reduction techniques.

---

## Q7. Define a line in geometry and give its mathematical representation.
**Answer:**  
A line is a straight path extending infinitely in both directions.  
In vector form:  
\\[
Equation:  
\\[
ax + by + cz + d = 0
\\]  
where $(a, b, c)$ is the normal vector to the plane.  
A line is 1-dimensional, while a plane is 2-dimensional.
## Q8. Define a plane in 3D space and explain how it differs from a line.
**Answer:**  
A plane is a flat 2D surface extending infinitely in 3D space.  
Equation:  
\\[
ax + by + cz + d = 0
\\]  
A line is 1-dimensional, while a plane is 2-dimensional.

---

## Q9. What is a hyperplane, and why is it important in machine learning (e.g., SVMs)?
**Answer:**  
A hyperplane is a higher-dimensional generalization of a plane.  
In machine learning, it is used to separate data into different classes (e.g., in Support Vector Machines).

---

## Q10. Define a matrix. How is it different from a vector?
**Answer:**  
A vector is a special case of a matrix with either a single row (row vector) or a single column (column vector).
A vector is a special case of a matrix with a single row or column.

---

## Q11. List the main types of matrices (e.g., square, diagonal, identity, zero).
**Answer:**  
- Square matrix  
- Diagonal matrix  
- Identity matrix  
- Zero matrix  

---

## Q12. What are the most common matrix operations (addition, subtraction, multiplication, transpose)?
**Answer:**  
- Addition: element-wise sum  
- Subtraction: element-wise difference  
- Multiplication: row × column rule  
- Transpose: rows become columns