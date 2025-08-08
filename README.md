Siddhant Arora 

24070123107 

ENTC B1

# Matrix Operations in C++

**Theory:**  
A matrix is a two-dimensional array of numbers arranged in rows and columns.  
Matrix operations are fundamental in mathematics, computer science, engineering, and data processing.  
They are used in solving linear equations, graphics transformations, cryptography, scientific simulations, and more.  
In programming, matrices are often represented using 2D arrays, and basic operations like addition, multiplication, transpose, and diagonal sums form the foundation for advanced computations.

This repository contains multiple C++ programs for performing various matrix operations, including:

1. **Matrix Addition**
2. **Row Comparison in a Matrix**
3. **Sum of Main Diagonal Elements**
4. **Matrix Multiplication**
5. **Matrix Input and Display**
6. **Transpose of a Matrix**

---

## 1. Matrix Addition

**Description:**  
Adds two matrices if they have the same dimensions.

**Algorithm:**
1. Input `r1`, `c1` for the first matrix and `r2`, `c2` for the second.
2. Check if `r1 == r2` and `c1 == c2`.
3. If true:
   - Input both matrices.
   - Add corresponding elements and store in the result matrix.
4. Display the sum matrix.
5. Otherwise, display "Not same dimension".

---

## 2. Comparing First and Second Rows of a Matrix

**Description:**  
Compares the first and second rows element-by-element.

**Algorithm:**
1. Input number of rows `r` and columns `c`.
2. Input the matrix elements.
3. If `r < 2`, display an error.
4. Compare elements of row 0 and row 1 for each column.
5. Print whether each column value is equal or not.

---

## 3. Sum of Main Diagonal Elements

**Description:**  
Calculates the sum of diagonal elements in an `n x n` matrix.

**Algorithm:**
1. Input size `n`.
2. Input matrix elements.
3. Initialize `sum = 0`.
4. For each `i` from `0` to `n-1`, add `m[i][i]` to `sum`.
5. Display the sum.

---

## 4. Matrix Multiplication

**Description:**  
Multiplies two matrices if the number of columns of the first equals the number of rows of the second.

**Algorithm:**
1. Input `r1`, `c1` for the first matrix and `r2`, `c2` for the second.
2. If `c1 != r2`, display "Matrix multiplication not possible".
3. Input both matrices.
4. For each cell `(i, j)` in the result:
   - Set `result[i][j] = 0`.
   - For `k = 0` to `c1-1`, add `m1[i][k] * m2[k][j]` to `result[i][j]`.
5. Display the product matrix.

---

## 5. Matrix Input and Display (3x3)

**Description:**  
Takes a fixed-size `3x3` matrix input and displays it.

**Algorithm:**
1. Loop over `i` and `j` to input matrix values.
2. Loop again to display the matrix in tabular form.

---

## 6. Transpose of a Matrix

**Description:**  
Finds the transpose of a matrix by swapping rows with columns.

**Algorithm:**
1. Input number of rows `r` and columns `c`.
2. Input the matrix elements.
3. For each `(i, j)`, assign `t[j][i] = m[i][j]`.
4. Display the transpose.

---

## Conclusion

These programs collectively demonstrate the basic matrix operations in C++.  
They cover:
- **Addition** for matrices of equal dimensions.
- **Row comparison** for data analysis.
- **Diagonal sum** for square matrices.
- **Multiplication** for compatible matrices.
- **Simple display** for fixed-size input.
- **Transpose** for matrix transformation.
