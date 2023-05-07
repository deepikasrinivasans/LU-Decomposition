# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np.
2. Import lu from scipy.linalg.
3. Declare the array as A.
4. Assign P,L,U (Pivot matrix,L matrix and U matrix) to lu of A.
5. Print L and U
## Program:
(i) To find the L and U matrix
```
#Program to find the L and U matrix.
#Developed by: DEEPIKA.S
#RegisterNumber: 212222230028
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
##Output:
![image](https://user-images.githubusercontent.com/119393935/236671331-a10f2597-6ec1-47d6-b0e9-fb8707e953ec.png)
```
##Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
```

(ii) To find the LU Decomposition of a matrix
```
#Program to find the LU Decomposition of a matrix.
#Developed by: DEEPIKA.S 
#RegisterNumber: 212222230028
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = eval(input())
b = eval(input())
lu,piv = lu_factor(A)
x = lu_solve((lu,piv), b)
print(x)
```
## Output:
![image](https://user-images.githubusercontent.com/119393935/236671394-6d19dd5e-f4c2-4f44-88ce-c385dc23b256.png)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

