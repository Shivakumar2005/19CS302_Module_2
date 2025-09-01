# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:01/09/2025
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1. Start the program.
2. Declare variables: num, digit, sum = 0.
3. Read the number from the user.
4. Use a do while loop: 
5. Stop the program.  

## Program:

#include <stdio.h>

int main() {
    int num, digit, sum = 0;

    printf("Enter a number: ");
    scanf("%d", &num);

    int temp = num;  // To keep original number for reference

    do {
        digit = num % 10;
        if (digit % 2 != 0) {
            sum += digit;
        }
        num = num / 10;
    } while (num > 0);

    printf("Sum of odd digits in %d = %d\n", temp, sum);

    return 0;
}
## Output:

<img width="1537" height="671" alt="image" src="https://github.com/user-attachments/assets/af355394-51bc-4a90-a175-bc84e0e115a3" />


## Result:
Thus the program was executed and the output was verified successfully.
