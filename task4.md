#include <stdio.h>
int main() {
	float salary;
	int age;
	printf("enter your salary:");
	scanf("%f",&salary);
	printf("enter your age:");
	scanf("%d",&age);
	if (salary>=40000 && age>=25){
		printf("your loan approved\n");
	}else {
		printf("your loan is not approved\n ");
	}
	return 0;
}
