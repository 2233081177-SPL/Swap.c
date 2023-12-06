# Swap.c
#include <stdio.h>

int main()
{
    int a,b;
    printf("Enter the two value of swap\n");
    scanf("%d%d,&a,&b");
    printf("before swaping a = %d and b %d=",a,b);
    a=a+b;
    b=a-b;
    a=a-b;
    printf("after swapping a= %d and b= %d",a,b);
    return 0;
}
