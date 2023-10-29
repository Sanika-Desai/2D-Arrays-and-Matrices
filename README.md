# AIM
2D-Arrays-and-Matrices

# THEORY

A multi-dimensional array can be termed as an array of arrays that stores homogeneous data in tabular form. This article covers Multidimensional Arrays in C++ with working examples. It also covers 2-dimentional and 3-dimentional array.


Two-Dimensional Array

The most basic type of multidimensional array is a two-dimensional array. For ease of understanding, we can think of a two-dimensional array as an array of one-dimensional arrays.

The simplest way to declare a 2-D array of sizes a and b is as follows:

data_type arr_name[a][b];

The type of data that will be stored is indicated here by the variable data type.

A two-dimensional integer array, say, “a,” of size 7,10, can be declared as follows:

int x[7][10]; Two-dimensional array elements are often identified by the notation a[i] [j], where i denote the row number, and ‘j’ denotes the column number

Representation of 2-D Array Row and column indices are used to access elements in two-dimensional arrays.

A[0] [0] A[0] [1] A[0] [2]

A[1] [0] A[1] [1] A[1] [2]

A[2] [0] A[2] [1] A[2] [2]

# ALGORITHM

Take matrix input from user and display it
1.We first get the number of rows and columns from the user.

2.We then declare a 2D array (matrix) with the specified dimensions.

3.We use nested loops to iterate through the matrix and input the elements from the user.

4.Finally, we use another set of nested loops to display the matrix.

5.Compile and run this C++ program, and it will take matrix input from the user and display it on the screen.

Addition of matrix
Start

Declare variables for the number of rows and columns for the matrices (let's call them rows and cols).

Get the dimensions (rows and cols) of the matrices from the user.

Declare two 2D arrays (matrices) of size rows x cols: matrix1 and matrix2.

Input the elements of matrix1 and matrix2 from the user using nested loops.

Declare another 2D array (resultMatrix) of the same size (rows x cols) to store the result.

Perform matrix addition using nested loops:

For each element at position (i, j) in resultMatrix:
resultMatrix[i][j] = matrix1[i][j] + matrix2[i][j]
Display the resultMatrix, which contains the sum of the two matrices.

End

Multiplication of Matrix
Start

Declare variables for the number of rows and columns for the first matrix (matrix1Rows, matrix1Cols) and the second matrix (matrix2Rows, matrix2Cols).

Get the dimensions (rows and columns) of matrix1 and matrix2 from the user.

Check if matrix1Cols is equal to matrix2Rows. If not, exit the program with an error message because matrix multiplication is not possible.

Declare three 2D arrays:

matrix1 of size matrix1Rows x matrix1Cols
matrix2 of size matrix2Rows x matrix2Cols
resultMatrix of size matrix1Rows x matrix2Cols
Input the elements of matrix1 and matrix2 from the user using nested loops.

Perform matrix multiplication using three nested loops:

For each element at position (i, j) in resultMatrix:
Initialize resultMatrix[i][j] to 0.
Perform the dot product of the ith row of matrix1 and the jth column of matrix2 to calculate resultMatrix[i][j].
Display the resultMatrix, which contains the product of the two matrices.

End

Diagonal Addition
Start

Declare variables for the number of rows and columns of the matrix (rows and cols).

Get the dimensions (rows and cols) of the matrix from the user.

Declare a 2D array (matrix) of size rows x cols to store the matrix elements.

Input the elements of the matrix from the user using nested loops.

Initialize a variable (diagonalSum) to 0. This variable will store the sum of the diagonal elements.

Use a loop to iterate through the diagonal elements of the matrix:

For each element at position (i, i), add matrix[i][i] to diagonalSum.
Display the value of diagonalSum, which contains the sum of the diagonal elements.

End

Transpose of Matrix
Start

Declare variables for the number of rows and columns of the original matrix (rows and cols).

Get the dimensions (rows and cols) of the original matrix from the user.

Declare a 2D array (originalMatrix) of size rows x cols to store the original matrix elements.

Input the elements of the original matrix from the user using nested loops.

Declare a new 2D array (transposeMatrix) of size cols x rows to store the transposed matrix.

Use nested loops to copy the elements from the original matrix to the transposed matrix with swapped rows and columns:

For each element at position (i, j) in the original matrix, assign originalMatrix[i][j] to transposeMatrix[j][i].
Display the transposed matrix (transposeMatrix).

End

Campare elements of first row to the second row
Start

Declare variables for the number of rows and columns of the matrix (rows and cols).

Get the dimensions (rows and cols) of the matrix from the user.

Declare a 2D array (matrix) of size rows x cols to store the matrix elements.

Input the elements of the matrix from the user using nested loops.

Initialize a boolean variable (rowsEqual) to true. This variable will be used to track if the elements of the first row are equal to the corresponding elements of the second row.

Use a loop to compare the elements of the first row to the second row:

For each column index (i) from 0 to cols-1:
If matrix[0][i] is not equal to matrix[1][i], set rowsEqual to false and break out of the loop.
If rowsEqual is true, display a message indicating that the two rows are equal. Otherwise, display a message indicating that the two rows are not equal.

End

# OUTPUT

Take matrix input from user and display it

![image](https://github.com/Sanika-Desai/2D-Arrays-and-Matrices/assets/142314095/08f9a966-d44d-438b-ac4c-280252a1e73f)

Addition of matrix

![image](https://github.com/Sanika-Desai/2D-Arrays-and-Matrices/assets/142314095/8b8d5461-33f3-4faf-bc05-9679ec7f3925)

Multiplication of Matrix

![image](https://github.com/Sanika-Desai/2D-Arrays-and-Matrices/assets/142314095/5acaf7b0-6965-464a-a04d-ccde944e875e)

Diagonal Addition

![image](https://github.com/Sanika-Desai/2D-Arrays-and-Matrices/assets/142314095/3424cb71-f1f0-4090-8c40-0177ca72635a)

Transpose of Matrix

![image](https://github.com/Sanika-Desai/2D-Arrays-and-Matrices/assets/142314095/278a75e8-d06b-4409-b18c-59df7941fe69)

COmpare elements of first row to the second row

![image](https://github.com/Sanika-Desai/2D-Arrays-and-Matrices/assets/142314095/ded01fa4-de99-4826-93db-0640c35827cf)
