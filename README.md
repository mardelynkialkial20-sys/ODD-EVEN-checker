#include <stdio.h>

int main(){

   int number;
   
   printf("Enter a number:");
   scanf("%d", &number);
   
   if(number %2 == 0) {
   printf("%d is EVEN.\n", number);
   }

   else{
   printf("%d is ODD.\n", number);
   }
 
 return 0;

}

