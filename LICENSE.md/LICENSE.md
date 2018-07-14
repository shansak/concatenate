#include<stdio.h>
#include<string.h>


int main()

{
   char a[40],b[40];
   
   printf("enter the first string");
   gets(a);
   
   printf("enter the second string");
   gets(b);
   
   strcat(a,b);
   
   printf("after concatenatenation %s",a);
   
   return 0;
   
   
   }
