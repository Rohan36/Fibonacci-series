# Fibonacci-series
how to create a fibonacci series
#include <stdio.h>



int main()

{

    

    int i,x;

    printf("enter fibo num:\n");

    scanf("%d",&x);

    int num[x];

    num[0]=0;

    num[1]=1;

    printf("%d\n",num[0]);

    printf("%d\n",num[1]);

    for(i=2;i<x;i++)

    {

        num[i]=num[i-2]+num[i-1];

        printf("%d\n",num[i]);

    }

    return 0;

}
