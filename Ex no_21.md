# EX 21 C program to calculate the area of a triangle using pointer.
## DATE:
## AIM:
To write a C program to calculate the area of a triangle using pointer.

## Algorithm
1. Start the program.
2. Declare three float variables (base, height, area).
3. Prompt and read base and height using `scanf`.
4. Calculate area using formula: area = 0.5 × base × height.
5. Print the area and stop the program.
6. End
   

## Program:
```
#include <stdio.h>
int main() {
 float base, height, area;
 float *pBase = &base, *pHeight = &height;
 scanf("%f", pBase);
 scanf("%f", pHeight);
 area = 0.5 * (*pBase) * (*pHeight);
 printf("%.2f\n", area);
}
```

## Output:
<img width="462" height="172" alt="image" src="https://github.com/user-attachments/assets/842b4483-9ee9-4654-aa8d-c40323a21e58" />

## Result:
Thus the program was executed and the output was verified successfully.
