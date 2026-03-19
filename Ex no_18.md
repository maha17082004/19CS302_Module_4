# EX 18 C program to find frequency of a character in the given input.
## DATE:
## AIM:
To write a C program to find frequency of a character in the given input.

## Algorithm
1. Start the program.
2. Declare variables for string, character, and count.
3. Read the string and the character from the user.
4. Traverse the string and count occurrences of the character.
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
<img width="278" height="296" alt="image" src="https://github.com/user-attachments/assets/b09bf523-1eb3-47fa-bf58-669652c6649e" />



## Result:
Thus the program was executed and the output was verified successfully.
