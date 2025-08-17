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
import numpy as np
A = np.array([[5, -3, -10],
              [2,  2,  -3],
              [-3, -1,  5]])
B = np.array([-9, 4, -1])
solution = np.linalg.solve(A, B)
solution = np.round(solution)
formatted_solution = [int(num) if num.is_integer() else num for num in solution] 
x, y, z = formatted_solution
print(f"[{x}.  {y}. {z}.]")
```
## Output:
![alt text](<Screenshot 2025-08-14 093027.png>)
## Result: 
Thus the solutions for the linear equations are successfully solved using python program

