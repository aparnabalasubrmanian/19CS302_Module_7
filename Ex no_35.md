
# EX 35 C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.
## DATE: 16.8.25
## AIM:
To write a C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.

## Algorithm
1. Start.
2. Define a variables.
3. Write a program to read a file name from user and create that file and insert student
roll numbers in to that file.
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

int main()
{
    FILE *fp;

    fp = fopen("Hospital.txt", "w");
    printf("Hospital.txt File Created Successfully\n");
    printf("Hospital.txt File Opened\n");

    fclose(fp);
    printf("Hospital.txt File Closed");

    return 0;
}

```

## Output:

<img width="816" height="153" alt="image" src="https://github.com/user-attachments/assets/91c2f577-9cc2-4daf-8e0f-1acd9bd6f522" />



## Result:
Thus the program was executed and the output was verified successfully.
