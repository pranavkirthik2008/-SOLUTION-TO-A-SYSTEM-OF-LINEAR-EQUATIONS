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
#Program to find the solution for the given linear equations.
#Developed by: PRANAV KIRTHIK SS
#RegisterNumber:212225230212
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a = np.array([[1,3],[2,5]])
b = np.array([5,-3])

x = np.linalg.solve(a,b)

print(x)
## Output:
<img width="423" height="189" alt="Screenshot 2026-05-16 090828" src="https://github.com/user-attachments/assets/129db36d-343a-4e83-bd9f-0b833fac27b2" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

