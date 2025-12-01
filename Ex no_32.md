
# EX 32 C program to display Hardware details such as price, product name and price using structure.
## DATE: 16.8.25
## AIM:
To write a C program to display Hardware details such as price, product name and price using structure.

## Algorithm
1. Start.
2. Define a variables.
3. Write a program to display hardware details such as price, product name and price 
using structure.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End. 

## Program:
```
/*
Developed by: Aparna RB
RegisterNumber:  212222220005
*/
#include <stdio.h>

struct hardware
{
    char code[50];
    char product[50];
    int price;
};

int main()
{
    struct hardware h[3];
    int i;

    for (i = 0; i < 3; i++)
        scanf("%s %s %d", h[i].code, h[i].product, &h[i].price);

    for (i = 0; i < 3; i++)
    {
        printf("QRcode:%s\n", h[i].code);
        printf("product:%s\n", h[i].product);
        printf("price :%d\n", h[i].price);
    }

    return 0;
}

```

## Output:
![image](https://github.com/user-attachments/assets/511eb4f2-6cd2-4774-ae07-7a0ddc859a5d)

## Result:
Thus the program was executed and the output was verified successfully.
