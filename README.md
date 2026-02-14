# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 212225230123
# Developed By: Kamesh A
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,1)
print(f"{b:.2f}")


# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,2)
print(f"{b:.2f}")


# Infinity Norm of a Matrix


import numpy as np 
a=np.array(eval(input()))
n=np.linalg.norm(a,np.inf)
print(f"{n:.2f}")


```
## Output:
### 1-Norm of a Matrix
<img width="1430" height="853" alt="image" src="https://github.com/user-attachments/assets/5352d217-c890-4b9a-9ffe-81ef8cbcfbb5" />


### 2-Norm of a Matrix
<img width="1304" height="814" alt="image" src="https://github.com/user-attachments/assets/31959b0e-212a-4f12-917e-508304406d0c" />

### Infinity Norm of a Matrix
<img width="1293" height="783" alt="image" src="https://github.com/user-attachments/assets/7cc6682e-e994-417e-9749-71374cb228ff" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
