# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library
2. Import lu function from scipy library
3. Solve LU decomposition using lu_solve() function.
4. Print the value


1. Import numpy
2. From scipy.linalg import lu,lu_factor ,lu solve respectively
3. Get the input matric values from user using eval
4. Print and solve LU decomposition using lu_solve() function.



## Program:
~~~
Program 1
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)

Program 2
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)

~~~



## Output:
![OUTPUT]![Alt text](<Screenshot from 2024-12-20 20-51-50.png>)
![OUTPUT]![Alt text](<Screenshot from 2024-12-20 20-51-50.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

