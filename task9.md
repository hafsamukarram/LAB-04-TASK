#include <stdio.h>
int main () {
	float attendence;
	int internalMarks;
	printf("enter your attendence percentage:");
	scanf("%f",&attendence);
	printf("enter your internal marks:");
	scanf("%d",&internalMarks);
	if (attendence>=75 && internalMarks>=40)
       printf("eligible for final exams\n");
    else
	   printf("not eligible for final exams\n");
	return 0;   
}
