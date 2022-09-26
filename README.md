# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement.


2. From scipy package import lu().


3. Get input from user and pass it as an array.


4. Get P, L, U matrix using lu()

5. Print L and U matrix

## Program:
(i) To find the L and U matrix
```python
Program to find L and U matrix using LU decomposition.
Developed by: P.Aravind samy
RegisterNumber: 22005040


import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P, L, U = lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```python
Program to solve a matrix using LU decomposition.
Developed by:P.Aravind samy
RegisterNumber: 22005040


import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, pivot = lu_factor(A)
x = lu_solve((lu,pivot),B)
print(x)

```

## Output:
![OUTPUT](/147100547-ec28a78f-3a9d-4b8e-9619-2e91a33b942e.png)

![OUTPUT](/147100590-1fb97dbd-f945-4495-81a4-78c8f9ddf799.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

