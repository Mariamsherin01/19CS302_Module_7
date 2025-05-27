# EX 32 C program to store any three fruits details such as name,colours& price then display the list of fruits which  belongs to the price greater than or equal to 2000 using structure.
## AIM:
To write a C program to store any three fruits details such as name,colours& price then display the list of fruits which  belongs to the price greater than or equal to 2000 using structure..

## Algorithm
1. Define a structure with members: name (string), color (string), and price (float or int).
2. Input details (name, color, price) for three fruits and store them in an array of structures.
3. Iterate through the array and check if the fruit's price is >= 2000.
4. If yes, print the fruit’s details.
5. End.
   

## Program:
```
/*
C program to store any three fruits details such as name,colours& price then display the list of fruits which  belongs to the price greater than or equal to 2000 using structure.
Developed by:  Mariam Sherin
RegisterNumber: 212222060143
#include <stdio.h>

struct Fruit {
    char name[20];
    char color[20];
    int price;
};

int main() {
    struct Fruit fruits[3];

    // Input details for three fruits
    for (int i = 0; i < 3; i++) {
       
       
        scanf("%s", fruits[i].name);
  
        scanf("%s", fruits[i].color);
    
        scanf("%d", &fruits[i].price);
    }

    // Display fruits with a price greater than or equal to 2000
  
    for (int i = 0; i < 3; i++) {
        if (fruits[i].price >= 2000) {
            printf("Name:%s\n", fruits[i].name);
            printf("colour:%s\n", fruits[i].color);
            printf("price :%d\n", fruits[i].price);
        }
    }

    return 0;
}

  
*/
```

## Output:

![image](https://github.com/user-attachments/assets/5ed7afaf-dcb7-4c7a-9903-ff88ef32b249)


## Result:
Thus the program was executed and the output was verified successfully.
