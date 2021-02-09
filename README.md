# Swapping
C program to perform the swapping of two numbers without using temporary variable

#include<stdio.h>
#include<conio.h>

void main()
{
    int x = 10, y = 15;
    x = x + y - (y = x);
    printf("x = %d and y = %d",x,y);
    getch();
}

x = 15 and y = 10
