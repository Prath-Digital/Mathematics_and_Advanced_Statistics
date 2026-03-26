# Self Excercise - 5.4

## Q1. What is an eigenvalue in the context of linear algebra?
**Answer:**  
An eigenvalue is a scalar $\lambda$ such that for a given square matrix $A$ and a non-zero vector $v$, the equation $Av = \lambda v$ holds; it represents how much the eigenvector $v$ is stretched or compressed during the linear transformation defined by $A$.

---

## Q2. What is an eigenvector, and how is it related to an eigenvalue?
**Answer:**  
An eigenvector is a non-zero vector that only changes in magnitude (its direction is preserved up to scalar multiplication) when a transformation is applied.  
It satisfies the equation:
$$
Av = \lambda v
$$  
where λ is the eigenvalue.

---

## Q3. How do we find eigenvalues of a square matrix?
**Answer:**  
Eigenvalues are found by solving the characteristic equation:
$$
\det(A - \lambda I) = 0
$$

---

## Q4. What equation is used to calculate eigenvectors once eigenvalues are known?
**Answer:**  
Eigenvectors are found by solving:
$$
(A - \lambda I)v = 0
$$

---

## Q5. Why are eigenvalues and eigenvectors important in dimensionality reduction techniques (like PCA)?
**Answer:**  
They help identify the directions (principal components), which are defined by the eigenvectors of the covariance matrix, where data varies the most. This allows reduction of dimensions while preserving important information.

---

## Q6. Give a real-world example of how eigenvectors are used in data science or machine learning.
**Answer:**  
In image compression, principal component analysis (PCA) uses the eigenvectors of the covariance matrix to represent images in a lower-dimensional space, preserving important features while reducing size (e.g., PCA in face recognition).

---

## Q7. What is matrix factorization in linear algebra?
**Answer:**  
Matrix factorization is the process of breaking a matrix into a product of simpler matrices to simplify computations; it is often used to make matrix operations such as solving linear systems or computing matrix inverses more efficient.

---

## Q8. Explain LU Decomposition and its purpose.
**Answer:**  
LU Decomposition expresses a matrix as:
$$
A = LU
$$  
Where L is a lower triangular matrix and U is an upper triangular matrix.  
It is used to efficiently solve systems of linear equations, especially when solving multiple systems with the same coefficient matrix but different right-hand sides.

---

## Q9. What is QR Decomposition and when is it used?
**Answer:**  
QR Decomposition expresses a matrix as:
$$
A = QR
$$  
Where Q is an orthogonal matrix and R is an upper triangular matrix.  
It is particularly useful for solving linear least squares problems because the orthogonality of Q simplifies computations and improves numerical stability.

---

## Q10. Mention one application of matrix decomposition in machine learning or data analysis.
**Answer:**  
Matrix decomposition, such as Singular Value Decomposition (SVD), is used in recommendation systems (like Netflix), where user-item matrices are factorized to predict preferences.