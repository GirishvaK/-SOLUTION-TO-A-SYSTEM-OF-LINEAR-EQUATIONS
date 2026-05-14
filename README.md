# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.solve(), we can find the solutions.
### Step 4: End the program
## Program:

#Program to find the solution for the given linear equations.

#Developed by: Girishva.K

#RegisterNumber: 212225040094

```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
le=np.linalg.solve(A,B)
print(le)
```
## Output:

<img width="1375" height="870" alt="image" src="https://github.com/user-attachments/assets/1ac56de3-6038-404f-86f8-b37fe36a7265" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

