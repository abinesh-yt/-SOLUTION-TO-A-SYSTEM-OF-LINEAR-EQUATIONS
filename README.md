<img width="1502" height="798" alt="image" src="https://github.com/user-attachments/assets/1a81814b-3c4a-4790-94da-eed401478208" /># -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
#Developed by: Abinesh A
#RegisterNumber:25017255

import numpy as np
a=np.array([[1,3],[2,5]])
b=np.array([5,-3])
c=np.linalg.solve(a,b)
print(c)


## Output:
<img width="1502" height="798" alt="Screenshot 2025-11-19 103817" src="https://github.com/user-attachments/assets/77aea510-0da5-424e-a1f3-1d0d9f4bdd60" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

