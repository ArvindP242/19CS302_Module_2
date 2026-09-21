# EX 6 C Program to print the string "KEYBOARD" n number of times.
## DATE:
## AIM:
To write a C Program to print the string "KEYBOARD" n number of times.

## Algorithm
1.Start

2.Declare an integer variable n

3.Read the value of n from the user

4.Repeat a loop from 1 to n

5.Print the string "KEYBOARD" inside the loop

6.End

## Program:
```
#include <stdio.h>

int main()

{

int n, i;

printf("Enter how many times you want to print KEYBOARD: ");

scanf("%d", &n);

for(i = 1; i <= n; i++) {

printf("KEYBOARD\n");

}

return 0;

}
```
## Output:
<img width="582" height="197" alt="image" src="https://github.com/user-attachments/assets/5ed537c1-0279-4286-b582-95aa7f0ecff5" />

## Result:
Thus the program was executed and the output was verified successfully.
