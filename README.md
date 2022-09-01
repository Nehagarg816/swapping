# swapping
This is a program for swapping of two numbers into each other.


#include<stdio.h>

int main()
{
    int a,b,c;
    printf("Enter one number a:");
    scanf("%d",&a);
    printf("Enter second number b:");
    scanf("%d",&b);
    c=a;
    a=b;
    b=c;
    printf("Value of a is %d",a);
    printf("\nValue of b is %d",b);
    return 0;
}
