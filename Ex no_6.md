# EX 6 C Program to print the string "KEYBOARD" n number of times.
## DATE:01/09/2025
## AIM:
To write a C Program to print the string "KEYBOARD" n number of times.

## Algorithm
1. Start the program.
2. Declare an integer variable n to store the number of times the string should be printed.
3. Read the value of n from the user.
4. Use a loop (for loop) to repeat printing the string "KEYBOARD" exactly n times. 
5. Stop the program.  

## Program:
#include <stdio.h>

int main() {
    int n, i;

    printf("Enter the number of times to print the string: ");
    scanf("%d", &n);

    for (i = 1; i <= n; i++) {
        printf("KEYBOARD\n");
    }

    return 0;
}
## Output:

<img width="1638" height="616" alt="image" src="https://github.com/user-attachments/assets/221b1d32-0e11-4d30-8274-71488b7bbb72" />


## Result:
Thus the program was executed and the output was verified successfully.
