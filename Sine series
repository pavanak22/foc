#include<stdio.h>

#include<math.h>

void sine(float*);

float fact(float);

void sine(float *x)

{

float i,j=0;

float sum=0;

for(i=1;i<8;i=i+2)

{

sum=sum+pow(-1,j++)*(pow(*x,i)/fact(i));

}

printf("%f",sum);

}

float fact(float i)

{

float f=1;

while(i>=1)

{

f=f*i;

i--;

}

return f;

}

void main()

{

float x;

printf("Enter x\n");

scanf("%f",&x);

sine(&x);

}
