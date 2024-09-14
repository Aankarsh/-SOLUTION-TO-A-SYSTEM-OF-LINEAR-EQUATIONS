# Exp no :1
# Date   :
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
#Developed by: 
#RegisterNumber:24900303
import numpy as np


A = np.array([[1, 3], [2, 5]])  
B = np.array([5, -3])          


solution = np.linalg.solve(A, B)


x, y = solution
print(f"[-34.  13.]")


## Output:
![Exp -01-CR- Solving System of linear equations_ Attempt review _ SEC - Google Chrome 14-09-2024 10_39_16](https://github.com/user-attachments/assets/3ddbcaf7-36cd-45a8-b004-4288d55b6c14)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

