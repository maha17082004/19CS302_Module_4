# EX 17 C Program to compare two strings without using strcmp().
## DATE:
## AIM:
To write a C Program to compare two strings without using strcmp().

## Algorithm
1. Start the program.
2. Declare variables for two strings and loop counters.
3. Read two string values from the user.
4. Compare the strings using nested loops and if condition.
5. Print whether strings are equal or not and stop the program.
  

## Program:
```
#include <stdio.h>
int main() {
 char str1[100], str2[100];
 int i = 0, flag = 0;
 scanf("%s", str1);
 scanf("%s", str2);
 while (str1[i] != '\0' || str2[i] != '\0') {
 if (str1[i] != str2[i]) {
 flag = 1;
 break;
 }
 i++; } 
if (flag == 0) 
printf("Strings are equal.\n");
else
 printf("Strings are not equal.\n");
 return 0;
}
```

## Output:

<img width="974" height="225" alt="image" src="https://github.com/user-attachments/assets/b9a04816-403e-478a-9981-3372afec681c" />


## Result:
Thus the program was executed and the output was verified successfully.
