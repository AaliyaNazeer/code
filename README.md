#include<stdio.h>
int main()
{
  int i,sum=0,n;
  printf("Enter the limit");
  scanf("%d",&n);
  for(i=0;i<n;i++)
   {
    sum=sum+i;
   }
   printf("The sum is %d",sum);
   return 0;
 }
