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
#Developed by: Gokul N
#RegisterNumber: 26009897

import numpy as np

a = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])

b = np.array([-9,4,-1])

x=np.linalg.solve(a,b)

print(x)


## Output:
<img width="1275" height="750" alt="image" src="https://github.com/user-attachments/assets/981b9102-27ba-4b35-a192-501a6a70873e" />

<img width="1301" height="230" alt="image" src="https://github.com/user-attachments/assets/489c298e-276e-436f-8ce7-9f8e529a8548" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

