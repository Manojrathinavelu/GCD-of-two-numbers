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
Developed by: R Manoj karthik
RegisterNumber:  22003728

def gcd():
    a=int(input())
    b=int(input())
    if a>b:
        smaller=b
    else:
        smaller=a
    for i in range(1,smaller+1):
        if(a%i==0 and b%i==0):
            ch=i
    print("GCD of two numbers is:",ch)
```

## Output:
![gcd](https://user-images.githubusercontent.com/119560395/214058961-6ebb75f2-ea2b-4cba-b68a-79e6a3bccc54.png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
