# EX 20 C program to convert the given string to lowercase without using string functions.
## DATE:
## AIM:
To write a C program to convert the given string to lowercase without using string functions.

## Algorithm
1. Start the program.
2. Declare variables for two strings and loop counters.
3. Read two string inputs from the user using `scanf`.
4. Compare characters of both strings using nested loops and if condition.
5. Print whether the strings are equal or not and stop the program.


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
        i++;    }    
 if (flag == 0)         
printf("Strings are equal.\n"); 
 else 
        printf("Strings are not equal.\n"); 
    return 0; 
}
```

## Output:

<img width="729" height="163" alt="image" src="https://github.com/user-attachments/assets/0824b584-5cf8-4495-89f3-fa6cf155c908" />


## Result:
Thus the program was executed and the output was verified successfully.
