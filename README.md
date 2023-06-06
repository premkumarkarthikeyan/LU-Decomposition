# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

   1. Import numpy library using import statement

   2. From scipy package import lu_factor() and lu_solve().

   3. Get two inputs from user and pass it as matrix array.

   4. Find lu and pivot value of first marix using lu_factor().

   5. Find solution of the matrix by using lu_solve() by passing lu, pivot values as first argument and second matrix as second argument.

   6. Print the solution


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: prem kumar.k
RegisterNumber: 212222230111
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:  prem kumar.k
RegisterNumber:212222230111 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
![lu decomposition]()
![5a maths prem](https://github.com/premkumarkarthikeyan/LU-Decomposition/assets/119476243/4d1f43f4-afde-4fc3-b4eb-0f3f53a87433)
![5b maths prem](https://github.com/premkumarkarthikeyan/LU-Decomposition/assets/119476243/a361a73c-0234-4d3e-8707-06245e73ac50)

## Result:

Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

