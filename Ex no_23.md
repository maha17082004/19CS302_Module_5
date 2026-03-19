# EX 23 C program to store and display the name, id, age and salary of an employee using structure(using array of structure).
## DATE:
## AIM:
To write a C program to store and display the name, id, age and salary of an employee using structure(using array of structure).

## Algorithm
**Algorithm (5 Short Points):**

1. Start the program.
2. Declare structure for employee and variables (array of structure).
3. Read employee details (name, id, age, salary) using `scanf`.
4. Store details in the structure array.
5. Display the employee details and stop the program.
6. END
  

## Program:
```
#include<stdio.h> 
struct employee
{
int id,age,salary; 
char name[30];
}emp[100]; 
int main()
{
int i,n; 
scanf("%d",&n); 
for(i=0;i<n;i++)
{
scanf("%d %s %d %d",&emp[i].id,emp[i].name,&emp[i].age,&emp[i].salary);
}
printf("Employee Details\n"); 
for(i=0;i<n;i++)
printf("%d %s %d %d\n",emp[i].id,emp[i].name,emp[i].age,emp[i].salary);}
```

## Output:
<img width="1055" height="274" alt="image" src="https://github.com/user-attachments/assets/8d6a1dd0-d536-44b1-a741-d0c9ebf720e5" />


## Result:
Thus the program was executed and the output was verified successfully.
