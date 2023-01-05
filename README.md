# c-code
#include<stdio.h>
#include<string.h>
#include<math.h>
int main()
{
  float a,b;
  scanf_s("%f%f",&a,&b);
  printf("%d\n",a+b);
  return 0;
}



int main()
{
  float a,b,max;
  scanf_s("%f%f",&a,&b);
  max = (a>b?a:b);
  printf("%f\n",max);
  return 0;
}
