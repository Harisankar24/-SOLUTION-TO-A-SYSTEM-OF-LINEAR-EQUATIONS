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
#Developed by:Harisankar.s 
#RegisterNumber:212224240051
import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b=np.array([-9,4,-1])
c=np.linalg.solve(a,b)
print(c)
```


## Output:
![Screenshot 2025-03-21 143136](https://github.com/user-attachments/assets/48f09e39-d5b7-4fee-b140-d1255e544c4a)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

