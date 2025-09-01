# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).
## DATE:01/09/2025
## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm
1. Start the program.
2. Define two functions:
    multiply() → to perform multiplication of two numbers.
    divide() → to perform division of two numbers.
3. In each function:
   Read two numbers from the user.
   Perform the respective operation (multiplication or division).
   Display the result.
4. In the main() function, call multiply() and divide() one after another. 
5. Stop the program.  

## Program:
#include <stdio.h>

// Function to multiply two numbers
void multiply() {
    int a, b, result;
    printf("\nEnter two numbers for multiplication: ");
    scanf("%d %d", &a, &b);
    result = a * b;
    printf("Multiplication of %d and %d = %d\n", a, b, result);
}

// Function to divide two numbers
void divide() {
    int a, b;
    float result;
    printf("\nEnter two numbers for division: ");
    scanf("%d %d", &a, &b);
    if (b == 0) {
        printf("Division by zero is not possible.\n");
    } else {
        result = (float)a / b;
        printf("Division of %d by %d = %.2f\n", a, b, result);
    }
}

int main() {
    multiply();
    divide();
    return 0;
}

## Output:

<img width="1625" height="677" alt="image" src="https://github.com/user-attachments/assets/0a1b8251-ec7f-4b58-977b-e3bab0ca09d9" />


## Result:
Thus the program was executed and the output was verified successfully.
