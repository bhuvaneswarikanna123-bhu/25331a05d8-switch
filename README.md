# 25331a05d8-switch
#include <stdio.h>
int main() {
int a,b, choice;
printf("enter two numbers");
scanf("%d %d ", &a, &b );
printf("\n1.addition\n2.subtraction\n3.multiplication\n4.division\n");
printf("enter your choice:");
scanf("%d ", & choice);
switch (choice) {

case 1:
printf("result= %d\n",a+b);
break;

case 2:
printf("result = %d\n",a-b);
break;

case 3:
printf("result = %d\n ",a*b);
break;

case 4:
printf("result = %d\n",a/b);
break;

default:
printf("invalid choice!\n");
}
return 0;
}
