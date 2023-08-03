#include<stdio.h>
int fact(int);
void main()
{
int num,fac;
printf("enter the positive number");
scanf("%d",&num);
fac=fact(num);
printf("factorial of %d is %d",num,fac);
}
int fact(int x)
{
if(x==0||x==1)
return 1;
else
return x*fact(x-1);
}
