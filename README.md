WAP TO FIND POWER OF A NUMBER 

#include<stdio.h>
int main(void)
{       
    int base, exponent, result = 1;
    printf("Enter base: ");
    scanf("%d", &base);
    printf("Enter exponent: ");
    scanf("%d", &exponent);
    int i = 1;
    while(i <= exponent)
    {
        result *= base;
        i++;
    }
    printf("%d^%d = %d", base, exponent, result);
    return 0; 
   }
WAP TO FIND MAX BETWEEN TWO NUMBER


   #include <stdio.h>
int  main(){
  int i, f = 1, num; 
  printf("Input the number : ");
  scanf("%d", &num); 
  for(i = 1; i <= num; i++) 
      f = f * i;  
  printf("The Factorial of %d is: %d\n", num, f);
   return 0; 
}

WAP TO FIND FACTORIAL OF A NUMBER


#include<stdio.h>
main()
{
	int a,b;
	printf("Enter two numbers:\n");
	scanf("%d%d",&a,&b);
	if(a>b)
	printf("%d is a maximum number\n",a);
	else
	printf("%d is a maximum number\n",b);	
}
