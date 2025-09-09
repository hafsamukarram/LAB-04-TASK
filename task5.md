#include <stdio.h>
int main () {
	float num1,num2;
	int choice;
	printf("enter first number:");
	scanf("%f",&num1);
	printf("enter second number:");
	scanf("%f",&num2);
	printf("choose operation\n");
	printf("1. addition\n");
	printf("2. subtraction\n");
	printf("3. multiplication\n");
	printf("4. division");
	printf("enter your choice(1-4):");
	scanf("%d",&choice);
	switch (choice) {
		case 1:
		   printf("result:%.2f\n",num1+num2);
		   break;
		case 2:
		   printf("result:%.2f\n",num1-num2);
		   break;
		case 3:
		   printf("result:%.2f\n",num1*num2);
		   break;
		case 4:
		   if (num2 !=0)
		   printf("result:%.2f\n",num1/num2);
		   else
		   printf("error:cannot divide by zero!\n");
		   break;
		default:   
		   printf("invalid choice\n");
    }
    return 0;
}
