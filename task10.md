#include<stdio.h>
int main () {
	int balance,withdrawal;
	printf("enter your balance:");
	scanf("%d",&balance);
	printf("enter amount to withdraw:");
	scanf("%d",&withdrawal);
	if (withdrawal<=balance && withdrawal%500==0) {
		printf("withdrawal successful!\n");
	}else {
		printf("withdrawal rejected!\n");
	}
	return 0;
}
