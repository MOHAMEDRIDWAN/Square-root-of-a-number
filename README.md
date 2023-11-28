# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: Mohamed Ridwan
RegisterNumber:  23003133
*/
#Developed by: Mohamed Ridwan A
#Register Number: 23003133

def sqr(x):
    for i in range(10):
       x=0.5*(x+b/x)
    print("Square root of the number:",x)
x=int(input())
b=x
sqr(x)
```

## Output:
![image](https://github.com/MOHAMEDRIDWAN/Square-root-of-a-number/assets/146993368/646cb618-6f73-4f95-98bf-e9acb6d7db03)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
