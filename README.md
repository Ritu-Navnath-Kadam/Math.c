# Math.c
#include<stdio.h>
#include<math.h>

void main()
{
double x;
int ch;
printf("Enter any number \n ");
scanf("%lf",&x);

do{
printf("1.sine\n");
printf("2.cosine\n");
printf("3.log\n");
printf("4.e^x\n");
printf("5.Square root\n");
printf("6.Exit\n");

printf("Enter your choice \n");
scanf("%d",&ch);
switch (ch)
{
case 1:
printf("The sine of %0.2lf  is = %lf\n",x,sin(x));
break ;

case 2:
printf("The cosine of %0.2lf is = %lf\n",x,cos(x));
break ;

case 3:
printf("The log of %0.2lf is = %lf\n",x,log(x));
break ;

case 4:
printf("The exponential  of %0.2lf is = %lf\n",x,exp(x));
break ;

case 5:
printf("The square root of %0.2lf is = %0.2lf\n",x,sqrt(x));
break ;
}
}
while(ch!=6);
}
