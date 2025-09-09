#include <stdio.h>
int main() {
	int a,b,c;
	printf("enter first number:");
	scanf("%d",&a);
	printf("enter second number:");
	scanf("%d",&b);
	printf("enter third number:");
	scanf("%d",&c);
	if (a>b){
		if (a>c){
			printf("the largest number is:%d\n",a);
		}else {
			printf("the largest number is:%d\n",c);
        }
  } else {
  	    if(b>c){
  	    	printf("the largest number is :%d\n",b);
  	    }else {
  	    	printf("the largest number is:%d",c);
		  }	
		 }
    return 0;
}
