# Matrix Determinants

A **determinant** is a scalar value that can be computed from a square matrix. Determinants play a crucial role in linear algebra, especially in solving systems of linear equations, finding inverses of matrices, and understanding matrix properties.

## Definition

For a square matrix \( A \) of size \( n \times n \), the determinant is denoted as \( \det(A) \) or \( |A| \).

### 2x2 Matrix

For a matrix
\[
A = \begin{bmatrix}
a & b \\
c & d
\end{bmatrix}
\]
the determinant is:
\[
\det(A) = ad - bc
\]

### 3x3 Matrix

For a matrix
\[
A = \begin{bmatrix}
a & b & c \\
d & e & f \\
g & h & i
\end{bmatrix}
\]
the determinant is:
\[
\det(A) = aei + bfg + cdh - ceg - bdi - afh
\]

## Properties

- Only square matrices have determinants.
- If the determinant is zero, the matrix is **singular** (not invertible).
- Swapping two rows (or columns) changes the sign of the determinant.
- Multiplying a row (or column) by a scalar multiplies the determinant by that scalar.
- The determinant of a product: \( \det(AB) = \det(A)\det(B) \).

## Applications

- **Solving Linear Systems:** Cramer's Rule uses determinants.
- **Matrix Inverses:** A matrix is invertible if and only if its determinant is nonzero.
- **Geometry:** The absolute value of the determinant of a matrix whose columns are vectors gives the volume of the parallelepiped spanned by those vectors.

## Calculation Methods

- **Expansion by Minors:** Recursively expand along a row or column.
- **Row Reduction:** Transform the matrix to upper triangular form; the determinant is the product of the diagonal entries (adjusted for row swaps).

## Examplegit add .
git commit -m "Update Matrices notes"
git push

Calculate the determinant of
\[
B = \begin{bmatrix}
2 & 3 \\
1 & 4
\end{bmatrix}
\]
\[
\det(B) = (2 \times 4) - (3 \times 1) = 8 - 3 = 5
\]
