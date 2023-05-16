#include <stdio.h>

unsigned long factorial(unsigned short int);

float power(float, unsigned short int);

int main() {

	unsigned short n, i = 0;	float x, sum = 0;

	printf("n: ");

	scanf("%hu", &n);

	printf("x: ");

	scanf("%f", &x);

	while(i < n) {

		sum += power(x,i)/(float) factorial(i);

		i++;

	}

	printf("Sum upto %hd terms = %f", n, sum);

	return 0;

}

float power(float x, unsigned short n) {

	float pow = 1;

	while(n > 0) {

		pow *= x;

		--n;

	}

	return pow;

}

unsigned long factorial(unsigned short n) {

	unsigned long f;

	if(n == 0 || n == 1)

		return 1;

	else

		f = n * factorial(n-1);

	return f;

}
