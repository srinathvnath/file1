# file1
#include <stdio.h>
int fact(int x)
{
    int i,fact=1;
    for(i=1;i<=x;i++)
    {
        fact=fact*i;
    }
    return fact;
}
int main()
{
    int num,f;
    scanf("%d",&num);
    f=fact(num);
    printf("Factorial of number %d is %d",num,f);
    return 0;
}
