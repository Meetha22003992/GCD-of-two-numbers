# Find the GCD of two numbers

## AIM:
To write a python program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
Program to find the gcd of two number using function.
Developed by: Meetha Prabhu
RegisterNumber:  212222240065
def gcd():
    x=int(input())
    y=int(input())
    if x<y:
        small=x
    else:
        small=y
    for i in range(1,small+1):
        if(x%i==0 and y%i==0):
            res=i
    print("GCD of two numbers is:",res)
```

## Output:
![image](https://github.com/Meetha22003992/GCD-of-two-numbers/assets/119401038/135e7fe8-a686-4e17-b2ee-725b2c9cb1db)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
