# 2016-11-30


#include<stdio.h>

int main()
{
	int  i, n, sum;
	
	printf("enter n:");
	scanf("%d",&n);
	
	for(i=1;i<=n;i++){
		sum=sum+i;
	}
	
	printf	("sum of 1 to %d is %d",n,sum) ;
	
 return 0;
} 
