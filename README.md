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
Developed by: Visalan H
RegisterNumber:  212223240183
*/

def square_root(number):
    x=number
    for i in range(100):
        number=0.5*(number+(x/number))
    return number

number = float(input())
print(f"Square root of the number: {square_root(number)}")
```
## Output:
![image](https://github.com/Visalan-H/Square-root-of-a-number/assets/152077751/4e6e19f2-bb46-470b-8c5f-146df5c69e6d)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
