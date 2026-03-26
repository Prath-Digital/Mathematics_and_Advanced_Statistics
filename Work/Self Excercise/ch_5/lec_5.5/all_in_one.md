# Self Excercise - 5.5

## Q1. What is Singular Value Decomposition (SVD) in linear algebra?
**Answer:**  
Singular Value Decomposition (SVD) factorizes a matrix into three matrices:
$$
A = U \Sigma V^T
$$  
It decomposes a matrix into orthogonal components and singular values.

---

## Q2. How is SVD different from Eigenvalue decomposition?
**Answer:**  
- Eigenvalue decomposition applies only to square matrices.  
- SVD works for any matrix (square or rectangular).  
- SVD is more stable and widely used in machine learning.

---

## Q3. What are the three matrices obtained from SVD (U, Σ, Vᵀ), and what do they represent?
**Answer:**  
- U: Left singular vectors (orthogonal basis for rows)  
- Σ: Diagonal matrix of singular values (importance/scaling)  
- Vᵀ: Right singular vectors (orthogonal basis for columns)

---

## Q4. Mention one application of SVD in data compression or recommendation systems.
**Answer:**  
SVD is used in image compression to reduce storage while preserving quality, and in recommendation systems (like Netflix) to predict user preferences.

---

## Q5. What is Principal Component Analysis (PCA), and what is its main purpose?
**Answer:**  
PCA is a dimensionality reduction technique that transforms data into a new coordinate system with maximum variance.

---

## Q6. How does PCA use eigenvalues and eigenvectors?
**Answer:**  
PCA computes eigenvectors of the covariance matrix.  
- Eigenvectors → principal components  
- Eigenvalues → importance (variance explained)

---

## Q7. What does the first principal component represent in PCA?
**Answer:**  
It represents the direction of maximum variance in the dataset.

---

## Q8. Why is PCA often used for dimensionality reduction?
**Answer:**  
It reduces the number of features while preserving most of the important information (variance).

---

## Q9. What are some limitations of PCA?
**Answer:**  
- Assumes linear relationships  
- Sensitive to scaling  
- Hard to interpret components  
- May lose important information

---

## Q10. What is Linear Discriminant Analysis (LDA), and how does it differ from PCA?
**Answer:**  
LDA is a supervised dimensionality reduction technique.  
- PCA maximizes variance  
- LDA maximizes class separation

---

## Q11. How does LDA maximize class separability in data?
**Answer:**  
LDA maximizes the ratio of between-class variance to within-class variance.

---

## Q12. Mention one practical application of LDA in machine learning.
**Answer:**  
LDA is used in face recognition systems and classification problems.