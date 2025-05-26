# EX 7 C Program to Print a right triangle star Pattern

## AIM:
To write a C Program to Print a right triangle star Pattern

## Algorithm
1. Start.
2. Declare the variables i,j,k,n.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Enter number of rows and columns.
6. End.
      

## Program:
```
#include <stdio.h>
int main() {
 int i, j, rows;
 scanf("%d", &rows);
 for (i = 1; i <= rows; i++) {
 for (j = 1; j <= i; j++) {
 printf("*");
 }
 printf("\n");
 } return 0;
}

```

## Output:

![Screenshot 2025-05-26 131510](https://github.com/user-attachments/assets/6683db35-c2b0-41da-b6e6-52cc4877258c)


## Result:
Thus the program was executed and the output was verified successfully.
