# C-
记录大学四年代码
成绩转换
#include<stdio.h>
int main()
{
	int n;
	printf("please input grades\n");
	scanf("%d",&n);
	if(n>=0&&n<=59)
		n=1;
	if(n>=60&&n<=69)
		n=2;
	if(n>=70&&n<=79)	
  		n=3;
  	if(n>=80&&n<=89)	
  		n=4;
  	if(n>=90&&n<=100)	
  		n=5;
  	switch(n)
  	{
  		case 1:printf("成绩为等级为E\n");break;
  		case 2:printf("成绩为等级为D\n");break;
  		case 3:printf("成绩为等级为C\n");break;
  		case 4:printf("成绩为等级为B\n");break;
  		case 5:printf("成绩为等级为A\n");break;
  		default :printf("sore is  error\n");break;
	}
  		
 }
