#include<stdio.h>
#include<string.h>
int main()
{
char password [5];
printf("enter a password:");
scanf("%4s",password);
if(strcmp(password,2222)==0)
{
printf("password verified");
}
else
{
printf("password incorrect");
}
return0;
}
