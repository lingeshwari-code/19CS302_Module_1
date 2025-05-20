# EX 2 C program to check whether the attendance is PRESENT using simple if statement.
## DATE:
## AIM:
To write a program to check whether the attendance is PRESENT using simple if statement.

## Algorithm
1. Start the program.
2.Read the attendance percentage from the user.
3.Check if the percentage is greater than or equal to 75.
4.If true, display "Attendance is PRESENT".
5.End the program.
 

## Program:
```
/*
Program to check whether the attendance is PRESENT using simple if statement.
Developed by: Lingeshwari.D
RegisterNumber:  212223060135
*/
#include <stdio.h>

int main() {
    float percentage;

    printf("Enter attendance percentage: ");
    scanf("%f", &percentage);

    if (percentage >= 75.0) {
        printf("Attendance is PRESENT\n");
    }

    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/9d984e2e-a66e-4ca4-982d-7846818aa6ca)

## Result:
Thus the program was executed and the output was verified successfully.
