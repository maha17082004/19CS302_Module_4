# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.
## DATE:
## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
1. Start the program.
2. Declare variables for string, character, and frequency count.
3. Read the string and character from the user using `scanf`.
4. Traverse the string and increment count when the character matches.
5. Print the frequency and stop the program.
   

## Program:
```
#include<stdio.h>
#include<string.h>
int main()
{
int i,count=0,len;
char str[100],val[100];
scanf("%s %s",str,val);
len=strlen(str);
for(i=0;i<len;i++){
if(str[i]==val[0])
count++;
}printf("%d",count);}
```

## Output:
<img width="262" height="273" alt="image" src="https://github.com/user-attachments/assets/c3fbacce-617b-449e-9e58-9986565e0d59" />

## Result:
Thus the program was executed and the output was verified successfully.
