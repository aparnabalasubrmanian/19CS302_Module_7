
# EX 33 C program to read a file name from user and create that file using fopen().
## DATE: 16.8.25
## AIM:
To write a C program to read a file name from user and create that file using fopen().

## Algorithm
1. Start.
2. Define a variables.
3. Write a program to read a file name from user and create that file using fopen().
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
    char filename[100];
    FILE *fp;

    scanf("%s", filename);

    fp = fopen(filename, "w");
    if (fp != NULL)
        printf("%s File Created Successfully\n", filename);

    printf("%s File Opened\n", filename);

    fclose(fp);
    printf("%s File Closed", filename);

    return 0;
}

```

## Output:
![image](https://github.com/user-attachments/assets/34b6969e-6cfa-47d7-9996-4c1295536fce)

## Result:
Thus the program was executed and the output was verified successfully.
