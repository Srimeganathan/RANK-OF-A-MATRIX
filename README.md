# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start by importing the required NumPy library.
### Step 2: Define the given matrix as a NumPy array
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Print the result to display the rank of the matrix.
## Program:
~~~
#Program to find the rank of a matrix.
#Developed by: Srimeganathan S
#RegisterNumber: 212224230273
import numpy as np

A = np.array([[1, 2, 3],
              [3, 6, 9]])

rank = np.linalg.matrix_rank(A)
print(rank)
~~~
## Output:
<img width="1515" height="963" alt="Screenshot 2025-08-19 091448" src="https://github.com/user-attachments/assets/1bedea9f-68d5-4d58-8d06-c0d1f8b6b12c" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

