#include <stdio.h>
int main() {
	float billAmount,payableAmount;
	printf("enter total bill amount:");
	scanf("%f", &billAmount);
	if (billAmount>5000){
		payableAmount=billAmount*0.9;
	}else{
		payableAmount=billAmount;
	}
	printf("final payable amouunt:%.2f\n",payableAmount);
	return 0;
}
