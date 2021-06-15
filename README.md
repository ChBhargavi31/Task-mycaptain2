#include<studio.h>
Main()
{
 double first,second,temp;
 Printf("Enter first number:");
 Scanf("%lf",&first);
 Printf("Enter second number:");
 Scanf("%lf,&second");
 temp=first;
 first=second;
 second=temp;
Printf ("\nafter swapping,firstnumber=%2lf",first);
printf("after swapping,second number=%2lf",second);
return 0;
}

