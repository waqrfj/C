# C
#include<stdio.h>
/* Write a program to calculate the factorial series
1!+2!+3!+4!+.......+n!*/
int main(){
    int number,i ,fact=1,sum=0;
    printf("Enter the number\n");
    scanf("%d",&number);
    for(i=1;i<=number;i++)
    {
        fact=fact*i;
        sum=sum+fact;
    }
printf("The factorial of 1st %d is %d\n",number,fact);
printf("The sum of 1st %d terms of factorial is :%d\n",number, sum);
    
    return 0;
}
