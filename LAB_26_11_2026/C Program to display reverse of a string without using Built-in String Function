#include <stdio.h> 
#include <string.h> 
int main() 
{ 
 char str[100], temp; 
 int i, length; 
    
 printf("Enter a string: "); 
 scanf("%s", str); 
 length = strlen(str); 
 for (i = 0; i < length / 2; i++) 
 { 
   temp = str[i]; 
   str[i] = str[length - 1 - i]; 
   str[length - 1 - i] = temp; 
 } 
   printf("Reverse string: %s", str); 
   return 0; 
} 
