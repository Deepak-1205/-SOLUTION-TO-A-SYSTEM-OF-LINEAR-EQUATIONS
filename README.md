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
```python
#Program to find the solution for the given linear equations.
#Developed by: Deepak S
#RegisterNumber: 212224230053

import numpy as np

a=np.array([[1,-3],[3,1]])
b=np.array([0,10])
c=np.linalg.solve(a,b)
print(c)
```
## Output:
<img width="1296" height="901" alt="image" src="https://github.com/user-attachments/assets/35887afc-6b40-4aa5-953d-d1d7b5a4b6a4" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

