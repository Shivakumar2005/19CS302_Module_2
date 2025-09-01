# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE:01/09/2025
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
1. Start the program.
2. Define a function factorial(int n) which takes an integer argument and returns the factorial.
3. In the function:
   If n is 0 or 1, return 1.
   Otherwise, return n * factorial(n-1).
4. In the main function: 
5. Stop the program.  

## Program:
#include <stdio.h>

int factorial(int n) {
    if (n == 0 || n == 1)
        return 1;
    else
        return n * factorial(n - 1);
}

int main() {
    int num, result;

    printf("Enter a number: ");
    scanf("%d", &num);

    if (num < 0) {
        printf("Factorial is not defined for negative numbers.\n");
    } else {
        result = factorial(num);
        printf("Factorial of %d = %d\n", num, result);
    }

    return 0;
}

## Output:

<img width="1502" height="652" alt="image" src="https://github.com/user-attachments/assets/4b2e7e72-fb1b-4afe-9787-4ee17402bdcb" />


## Result:
Thus the program was executed and the output was verified successfully.
