# Exp-2b-Find the square root of a number
## Date-29.08.2023
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
Developed by: Kishore Kumar U
RegisterNumber: 23000800
def sqt(number,numbt=100):
    a=float(number)
    for i in range(numbt):
        number=0.5*(number+a/number)
    return number
a=int(input())
print("Square root of the number:",sqt(a))
*/
```

## Output:
![image](https://github.com/Kishorekumar22060/Square-root-of-a-number/assets/141472136/f5326dc6-fac1-4d9e-8fe0-a9256c2f64e0)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
