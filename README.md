# Flat Matrix Multiplication Function [C]

This function performs a matrix multiplication operation on two 2-D matrices represented as flat (1-D) matrices. At the level of assembly language, matrices are represented by flat 1-D arrays. At this level, values at a given row or column of the matrix are indexed by indexing through the 1-D array. The rows and columns of the matrix become an abstraction existing outside of the code. This script is meant to mirror that operation in C. 

This script generates two matrices represented as flat 1-D arrays, and then multiplies them, generating the result. The script outputs the memory address of the resultant matrix. 
