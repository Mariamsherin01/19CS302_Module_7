# EX 33 C program to create a file with name "Staff.txt"
## AIM:
To write a C program to create a file with name "Staff.txt"

## Algorithm
1. Use fopen() to open/create the file "Staff.txt" in write mode.
2. Check if the file pointer is NULL (file creation failed); if yes, print error and exit.
3. If file opened successfully, optionally write data or just proceed.
4. Close the file using fclose().
5. End.


## Program:
```
/*
C program to create a file with name "Staff.txt"
Developed by:  Mariam Sherin
RegisterNumber: 212222060143
#include <stdio.h>
#include<stdlib.h>
int main()
{
    FILE *fptr;
    fptr=fopen("Student.txt","w");
    if(fptr==NULL)
    {
        printf("Error!");
        //exit(1);
    }
    else
    {
        printf("File Created Successfully\n");
        printf("File Opened\n");
    }
    fclose(fptr);
    printf("File Closed\n");
    return 0;
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/0b7a7cb5-161b-462e-9bca-9563b9a95d43)


## Result:
Thus the program was executed and the output was verified successfully.
