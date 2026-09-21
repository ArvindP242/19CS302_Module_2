# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE:
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
1.Start the program and declare a function factorial(int) with return type.

2.Read a number from the user.

3.Call the factorial function with the number as an argument.

4.Compute factorial in the function using a loop and return result.

5.Display the result in main.

Program:
## Program:
```
#include <stdio.h>

// Function to calculate factorial
int factorial(int n)
{
    int i, fact = 1;
    for(i = 1; i <= n; i++)
    {
        fact *= i;
    }
    return fact;
}

int main() {
    int num, result;
    scanf("%d", &num);
    
    result = factorial(num);
    printf("Factorial value is: %d\n",result);
    
    return 0;
}

```

## Output:
<img width="880" height="195" alt="image" src="https://github.com/user-attachments/assets/4d43c72c-85ea-4a27-9b97-3f083c1e8be1" />


## Result:
Thus the program was executed and the output was verified successfully.
