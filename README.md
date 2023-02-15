# print-number
打印数字上的各个数
#include <stdio.h>
void print(int n)
{
  if(n>9)
 { 
	 print(n/10);
  }
   printf("%d ",n%10);
  
  
}
int main()
{
  int n;
printf("input a number:");
scanf("%d",&n);
 print(n);
}
