
# EX 21 C program to calculate the area of a triangle using pointer.

## AIM:
To write a C program to calculate the area of a triangle using pointer.

## Algorithm
1. Start.
2. Declare three variable value of type float.
3. Prompt the user to enter values.
4. Read the values using scanf.
5. Find the area of triangle using formula
6. End  

## Program:
```
/*
Developed by: Kaviyarasan S
RegisterNumber:  212222060117
*/
#include <stdio.h>

int main()
{
    float a, b, area;
    float *x = &a, *y = &b;

    scanf("%f %f", x, y);

    area = 0.5 * (*x) * (*y);

    printf("%.2f", area);

    return 0;
}


```

## Output:

![Screenshot 2025-04-30 154838](https://github.com/user-attachments/assets/61464af2-29b1-49a6-be06-80db54e3ef59)


## Result:
Thus the program was executed and the output was verified successfully.
