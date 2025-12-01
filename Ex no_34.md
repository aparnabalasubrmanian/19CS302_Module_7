
# EX 34 C program to read a file name from user and create that file and insert student roll numbers in to that file.
## DATE: 16.9.25
## AIM:
To write a C program to read a file name from user and create that file and insert student roll numbers in to that file.

## Algorithm
1. . Start.
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
    char filename[100];
    int n, i, roll;
    FILE *fp;

    scanf("%s", filename);

    fp = fopen(filename, "w");
    printf("%s Opened\n", filename);

    scanf("%d", &n);

    for (i = 0; i < n; i++)
    {
        scanf("%d", &roll);
        fprintf(fp, "%d\n", roll);
    }

    fclose(fp);
    printf("Data added Successfully");

    return 0;
}

```

## Output:
![image](https://github.com/user-attachments/assets/f59a3640-abda-4dbd-8118-218ea7c2f8f5)

## Result:
Thus the program was executed and the output was verified successfully.
