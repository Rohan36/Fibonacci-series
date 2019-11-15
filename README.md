# Fibonacci-series
how to create a fibonacci series
 #include<stdio.h>
main()
{
    int a=0;b=1,c,n;
    printf("%d%d",a,b);
    printf("Enter the number of terms:\n");
    scanf("%d",&n);
    for(int a=1;a<n-2;++a)
    {
       c=a+b;
       printf("%d",c);
    }
}