# EX 3 C program to find number of years based on principle,rate & simple interest.
## DATE:10-10-2025
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
1. Start the program.
2. Input the principal amount from the user.
3. Input the rate of interest from the user.
4. Input the simple interest from the user.
5. Calculate and display the number of years.  

## Program:
```
/*
Program to find number of years based on principle,rate & simple interest.
Developed by: MONIKA M
RegisterNumber: 212223060169

#include <stdio.h>

int main() {
    float principal, rate, interest, time;

    printf("Enter Principal amount: ");
    scanf("%f", &principal);

    printf("Enter Rate of interest: ");
    scanf("%f", &rate);

    printf("Enter Simple Interest: ");
    scanf("%f", &interest);

    time = (interest * 100) / (principal * rate);

    printf("Number of years: %.2f\n", time);

    return 0;
```

## Output:
<img width="398" height="217" alt="image" src="https://github.com/user-attachments/assets/b58b9cd0-14a5-4c17-b272-5e058249efb3" />

## Result:
Thus the program was executed and the output was verified successfully.
