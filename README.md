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
/*
Program to find the gcd of two number using function.
Developed by: VEERARAGAVAN V
RegisterNumber:  23004739
*/
def gcd():
    c=int(input())
    d=int(input())
    if c>d:
        min= d
    else:
        min=c
    for i in range(1,min+1):
        if(c%i==0 and d%i==0 ):
            gcd=i
    print("GCD of two numbers is:",gcd)
```
## Output:
![gcd of two number](gcd.png)
![Screenshot 2023-12-21 200922](https://github.com/veerargavanv27/GCD-of-two-numbers/assets/138955645/54d7eb7f-77ea-4c1c-8f2a-d997d4de7a29)
## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
