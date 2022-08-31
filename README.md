# pp
//RC phase shift oscillator
#include <stdio.h>
#include <math.h>
void main()
float f0,R,C,Rf;
float pi=3.142;
printf("enter the value of capacitance");
scanf("%f",&c);
f0= 1*1000;
R= 1/(2*pi*C*f0*(sqrt(6)));
Rf= 29*R;
printf("Resistance= %f\n",R);
printf("Rf= %f\n",Rf);
}
