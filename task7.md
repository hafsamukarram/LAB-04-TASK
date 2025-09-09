#include <stdio.h>
int main() {
	char password[4];
	printf("enter your password:");
	scanf("%s",password);
	if (strcmp(password,"1234")==0){
		printf("access granted\n");
	}else {
		printf("access denied\n");
	}
	return 0;
}
