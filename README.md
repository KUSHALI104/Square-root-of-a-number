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
Program to find the square root for the given number(newton's method) using function.
Developed by: KUSHALI P G
RegisterNumber:  23012804
def newton_method(number,number_iters=100):
    a=float(number)
    for i in range(number_iters):
        number=0.5*(number+a/number)
    return number
a=int(input())
print("Square root of the number:",newton_method(a))

```

## Output:
![image](https://github.com/KUSHALI104/Square-root-of-a-number/assets/150231135/0fe957bd-3d23-492b-8c20-3b9d831fbe03)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
