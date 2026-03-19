# EX 16 C program to find minimum between three fraction numbers using conditional operator.
## DATE:
## AIM:
To write a C program to find minimum between three fraction numbers using conditional operator.

## Algorithm
1. Start the program.
2. Declare variables a, b, c, and min.
3. Read values of a, b, and c from the user.
4. Compare a, b, and c to find the minimum value.
5. Print the minimum value and stop the program.
  

## Program:
```
#include <stdio.h>
int main() {
float a, b, c, min;
scanf("%f%f%f", &a, &b, &c);
// Finding minimum using conditional operator 
min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c);
printf("Minimum between %.3f, %.3f and %.3f = %.3f\n",a,b,c, min);
return 0;
}
```

## Output:

<img width="1151" height="220" alt="image" src="https://github.com/user-attachments/assets/f8677b1c-45f4-4c6b-b0fa-c6a0829049d8" />

## Result:
Thus the program was executed and the output was verified successfully.
