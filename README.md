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


#include<stdio.h>
int runnian(int a)
{
	int z = a % 4;
	return z;
}
int main()
{
	int a = 0;
	scanf_s("%d", &a);
	int qiu = runnian(a);
	if (qiu != 0)
	{
		printf("no");
	}
	else
	{
		printf("yes");
	}
	return 0;
}
