# 2-Norm of a matrix
## Aim
To write a program to find the 2-norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()
	2. The 2-Norm of a matrix is given by 
![norm](./normeqn1.jpg)
    
    3. Find the 2-norm of the matrix using np.linalg.norm()
	4. Print the norm of the matrix in two decimal places.
## Program:
```
Program to find 2-norm of a matrix.
Developed by:M.D.Harini
RegisterNumber: 22001980

import numpy as np
arr=np.array(eval(input()))
n=np.linalg.norm(arr,2)
print("{:.2f}".format(n))
```
##Output:
![Screenshot from 2022-09-28 10-17-11](https://user-images.githubusercontent.com/113497680/192689806-6d7b0b0c-1bc5-4238-bbbf-84c3c25b08ca.png)

## Result
Thus the program for 2-norm of a matrix is written and verified.
