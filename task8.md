#include<stdio.h>
int main () {
	float temperature;
	printf("enter temperature in celsius:");
	scanf("%f",&temperature);
	if (temperature>30)  
		printf("Hot Day\n");
    else 
		printf("Pleasant Day\n");
	
	return 0;
}
