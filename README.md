## DATE:

# EXP-3: DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: get the input from user
### Step 2: import math and initialise the two values
### Step 3: Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4:print the values in format
### Step 5: end the program
### PROGRAM:
```

DEVELOPED BY:A K PREETHI
REGISTER NUMBER:212223230156

import math

def dis(x1,x2,y1,y2):

    d=((x2-x1)**2+(y2-y1)**2) 
    
    g=math.sqrt(d)
    
    return g
    
x1=4

x2=10

y1=2

y2=6

g=dis(x1,x2,y1,y2)

print("{:.2f}".format(g))
```
  


### OUTPUT:
![image](https://github.com/user-attachments/assets/864d06db-4ee6-4938-a2e7-9ff095feae1a)



### RESULT:
Thus the program has been executed successfully.
Thus the program is executed successfully.
