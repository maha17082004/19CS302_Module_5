# EX 22 C program to count total number of even elements in an array using calloc().
## DATE:
## AIM:
To write a C program to count total number of even elements in an array using calloc().

## Algorithm
1. Start the program.
2. Declare variables and allocate memory for array using `calloc()`.
3. Read the number of elements and array values using `scanf`.
4. Traverse the array and count elements where element % 2 == 0.
5. Print the total number of even elements and stop the program.
6. End
 

## Program:
```
#include<stdio.h> 
#include<stdlib.h> 
int main()
{
int *arr,n,i,count=0; 
scanf("%d",&n); 
arr=(int*)calloc(1,sizeof(int)); 
for(i=0;i<n;i++)
{
scanf("%d",&arr[i]);
}
for(i=0;i<n;i++)
if(arr[i]%2==0) 
count++;
printf("Total even elements: %d",count);
}
```

## Output:
<img width="899" height="268" alt="image" src="https://github.com/user-attachments/assets/f4eb19f7-87ac-41a4-814b-69f0e485d772" />


## Result:
Thus the program was executed and the output was verified successfully.
