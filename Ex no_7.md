# EX 7 C Program to Print a right triangle star Pattern
## DATE:01/09/2025
## AIM:
To write a C Program to Print a right triangle star Pattern

## Algorithm
1. Start the program.
2. Declare integer variables i, j, and n.
3. Read the value of n (number of rows) from the user.
4. After printing stars in one row, move to the next line. 
5. Stop the program.  

## Program:
#include <stdio.h>

int main() {
    int n, i, j;

    printf("Enter the number of rows: ");
    scanf("%d", &n);

    for (i = 1; i <= n; i++) {
        for (j = 1; j <= i; j++) {
            printf("* ");
        }
        printf("\n");
    }

    return 0;
}

## Output:

<img width="1634" height="679" alt="image" src="https://github.com/user-attachments/assets/76740058-5f59-48a8-9d19-a3c6e8913a98" />


## Result:
Thus the program was executed and the output was verified successfully.
