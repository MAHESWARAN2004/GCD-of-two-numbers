# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

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
Program to write a program to find the GCD of two numbers using function.
Developed by:MAHESWARAN.K 
RegisterNumber:212222110023 
def gcd():
    num1,num2=int(input()),int(input())
    if num1<num2:
        smaller=num1
    else:
        smaller=num2
    for i in range(1,smaller+1):
        if num1%i==0 and num2%i==0:
            gcdvalue=i
    print("GCD of two numbers is:",gcdvalue)
```

## Output:

![Exp-2A](https://user-images.githubusercontent.com/119478181/232187067-01495126-328b-4a6b-b520-49758874d506.png)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
