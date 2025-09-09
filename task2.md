#include <stdio.h>
int main() {
	int age;
	int ticketAmount;
	printf("enter your age:");
	scanf("%d", &age);
	if (age<12){
		ticketAmount=200;
	}else if (age>=12 && age<18){
		ticketAmount=300;
	}else if (age>=18 && age<=60){
		ticketAmount=500;
	}else
	ticketAmount=250;
	printf("ticket amount is:%d\n",ticketAmount);
	return 0;
}
