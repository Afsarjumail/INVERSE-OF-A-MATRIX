# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
import numpy as np
### Step 2:
We have created a matrix using array and we will find inverse of this.
### Step 3:
We can find the inverse of the martix by using np.linalg.inv and passing the matrix.
### Step 4:
Finally, print the value of the inverse of the matrix.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Afsar jumail S
#RegisterNumber:212222240004
import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
sol=(np.linalg.inv(A))
print(sol)
```
## Output:
![Screenshot from 2023-03-27 15-37-53](https://user-images.githubusercontent.com/118343395/227912140-3963f18e-351b-4195-aeac-c1d3a518615c.png)

## Result:
Thus the inverse of given matrix is successfully solved using python program

