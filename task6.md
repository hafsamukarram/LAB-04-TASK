#include <stdio.h>
int main() {
	int userAge;
	printf("enter your age:");
	scanf("%d",&userAge);
	if (userAge>=18){
		printf("eligible to vote\n");
	}else{
		printf("not eligible to vote\n");
	}
	return 0;
}
