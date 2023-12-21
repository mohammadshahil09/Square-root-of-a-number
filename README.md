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
#Write a python programming to find a square root for the given number using function.
#Developed by:guntur shaik mohammad shahil
#Reference number:23011002
def newton_method(number,number_iters=100):
    a=float(number)
    for i in range(number_iters):
        number=0.5*(number+a/number)
    return number
a=int(input())
print("Square root of the number:",newton_method(a))
```

## Output:
![gcd of two number](gcd.png)
![image](https://github.com/mohammadshahil09/Square-root-of-a-number/assets/145742840/35d07058-c02c-4ebe-b6eb-f746687349b3)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
