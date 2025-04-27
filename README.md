# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
import the numpy module to use the built-in function for calculation 
### Step 2:
prepare the list from each linear equation and assign in np.array()
### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
end the program 
## Program:
```
import numpy as np
a=np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:
![image](https://github.com/user-attachments/assets/4db38bd6-eb7b-4fa0-994f-0e334d63b0bb)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

