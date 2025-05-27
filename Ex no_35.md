# EX 35 C program to create a file named "library.txt" and display messages on successful creation, opening, and closing of the file.

## AIM:
To write a C program to create a file named "library.txt" and display messages on successful creation, opening, and closing of the file.

## Algorithm
1. Create a file named "library.txt" using fopen() in write mode and write book details into it.
2. Close the file after writing using fclose().
3. Reopen the file in read mode using fopen().
4. Read and display the contents using fscanf() or fgets().
5. Close the file and end the program.


## Program:
```
/*
C program to create a file named "library.txt" and display messages on successful creation, opening, and closing of the file.
Developed by:  Mariam Sherin
RegisterNumber:   212222060143
#include <stdio.h>
int main()
{
    int y,i,j;
    char z[30],x[30];
    scanf("%d",&y);
    FILE *p;
    p=fopen("student.txt","w");
    for(i=0;i<y;i++)
    { 
        scanf("%d",&j);
        scanf("%s",z);
        scanf("%s",x);
        fprintf(p," %d %s %s\n",j,z,x);
        printf("%d %s %s\n",j,z,x);
       
    }
    fclose(p);
    printf("Data Read Successfully");
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/0171b2b7-f75a-400a-acb0-fb1a6197829d)


## Result:
Thus the program was executed and the output was verified successfully.
