#include <stdio.h>

int main(){
   int number;
   int even;
   int odd;
   
   printf("Enter a number:");
   scanf("%d", &number);
   
   if(number %2 == 0) {
   printf("%d is EVEN.\n", even);
   }
   else{
   printf("%d is ODD.\n", odd);
   }
 
 return 0;
}