# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by:  SARVAJITH.S.S
#RegisterNumber: 252225220091
import numpy as np
A=np.array([
    [5,-3,-10],
    [2,2,-3],
    [-3,-1,5]]
)
B=np.array([-9,4,-1])
soln=np.linalg.solve(A,B)
print(soln)
```

## Output:
<img width="1286" height="836" alt="Screenshot 2026-06-01 143613" src="https://github.com/user-attachments/assets/cb8cb589-d838-4eea-b40c-d9972fec19ae" />



## Result: 
Thus the solutions for the linear equations are successfully solved using python program

