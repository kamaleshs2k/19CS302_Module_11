# EX 55 C program to find a square of number using function with arguments without return type.
## DATE: 11/05/2025
## AIM:
To write a C program to find a square of number using function with arguments without return type.

## Algorithm
1.Define a function square() that takes an integer as an argument.

2.Inside the function, calculate the square of the number by multiplying it by itself.

3.Print the square of the number inside the function.

4.Call the square() function from main(), passing the number as an argument.

5.Ensure that there is no return value (void return type).  

## Program:
```
/*
C program to find a square of number using function with arguments without return type.
Developed by: Kamalesh S
RegisterNumber:  212223060108
*/
#include <stdio.h>

void square(int num)
{
    printf("Square of %d is %d\n", num, num * num);
}

int main()
{
    int num;

    printf("Enter a number: ");
    scanf("%d", &num);

    square(num);

    return 0;
}


```

## Output:

![image](https://github.com/user-attachments/assets/9f3b34c5-07a0-43b6-9af2-7deded917d9b)


## Result:
Thus the program was executed and the output was verified successfully.
