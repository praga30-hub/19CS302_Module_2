# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm
1. Start.
2.Declare the variables.
3.Prompt the user to enter a value.
4.Read the value using scanf.
5.Enter number for multiplication and division.
6.End.
   

## Program:
```
#include<stdio.h>
void multiply(int a,int b); 
void div(int a,int b);
int main ()
{
int a,b; 
scanf("%d%d",&a,&b); 
multiply(a,b);
div(a,b);
}
void multiply(int a,int b)
{
int product; 
product= a*b;
printf("Multiplication: %d",product);
}
void div(int a,int b)
{
int result; 
result=a/b;
printf("\nDivision: %d",result);
}

```

## Output:

![Screenshot 2025-05-26 131235](https://github.com/user-attachments/assets/401d37b9-ccf4-48c1-8dd0-ff8757c12ff2)



## Result:
Thus the program was executed and the output was verified successfully.
