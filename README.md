#include<stdio.h>

void main()
{
  int n,i=0 ;
  float Avg,sum=0, c;
  printf(" Enter N value:\n");
  scanf("%d",&n);
  for(i=0;i<n;i++)
  {
  printf(" Enter the value:\n");
  scanf("%f",&c);
  sum= sum+c;
  }
  Avg=(sum/n);
  
  printf("dispaly avg value: %f\n",Avg);

}
