# Write-a-program-to-find-the-largest-number-between-two-numbers

//Write a program to find the largest number between two numbers using if.

#include <stdio.h>

int main() 
{
    float num1,num2;
    printf("Enter 1st no.: ");
    scanf("%f", &num1);
    printf("Enter 2nd no.: ");
    scanf("%f", &num2);
    if (num1 > num2) {
        printf("num1 is greater than num2.\n");
    } else if (num2 > num1) {
        printf("num2 is greater than num1.\n");
    } else {
        printf("both numbers are equal.\n");
    }
    return 0;
}
