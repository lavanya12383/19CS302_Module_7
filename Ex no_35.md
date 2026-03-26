# EX 35 C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.
## DATE:17/3/26
## AIM:
To write a C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.

## Algorithm
Start.
Define a variables.
Write a program to read a file name from user and create that file and insert student roll numbers in to that file.
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End 

## Program:
```
/*
C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.
Developed by: ARIGALA LAVANYA
RegisterNumber:  212222060019
#include <stdio.h> 
int main() 
{ 
FILE *p; 
char name[100]; 
int num; 
int id; 
char text[100]; 
float m; 
scanf("%s",name); 
scanf("%d",&num); 
p=fopen("name","w"); 
printf("%s Opened\n",name); 
{ 
scanf("%d %s %f",&id,text,&m); 
fprintf(p,"%d %s %f",id,text,m); 
} 
fclose(p); 
printf("Data added Successfully"); 
*/
```

## Output:

<img width="572" height="338" alt="image" src="https://github.com/user-attachments/assets/da54e0b3-4d0d-43d8-b540-09d65bf7c993" />


## Result:
Thus the program was executed and the output was verified successfully.
