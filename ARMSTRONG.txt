#include<stdio.h>
#include<conio.h>
#include<math.h>
void main()
{
int a,b,c,d,e,f;
printf("enter a 3 digit number:");
scanf("%d",&a);
b=a/10;
c=a%10;
d=b/10;
e=b%10;
f=pow(c,3)+pow(d,3)+pow(e,3);
if(a==f)
{
printf("it is a armstrong number");
}
else
{
printf("it is not armstrong number");
}
getch();
}