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
<img width="1295" height="469" alt="image" src="https://github.com/user-attachments/assets/ac3ad909-3b2e-4ce6-9a62-b0f0c544e0cd" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

