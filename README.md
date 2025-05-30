# EX-06 - Looping
## NAME:Vembarasi.A.R
## REG NO:212224220120
## AIM:
Write a C program to print even numbers ranging from M to N (including M and N values).

## ALGORITHM:
1.	Declare two integer variables to store the values of M and N.
2.	Use the printf function to prompt the user to enter the values of M and N.
3.	Use the scanf function to read the values of M and N from the user.
4.	Use a loop (for or while) to iterate from M to N.
5.	Inside the loop, check if the current number is even.
6.	If the current number is even, print it.
7.	Continue the loop until you have iterated through all numbers from M to N.

## PROGRAM:
```
#include <stdio.h>
int main() {
    int m,n,i;
    scanf("%d %d", &m, &n);
    for(i=m;i<n;i++){
    if(i%2==0){
    printf("%d ",i);
}
}
printf("\n");
    return 0;
}
```

## OUTPUT:
![Screenshot 2025-04-28 140603](https://github.com/user-attachments/assets/97be7e16-af1b-4607-aec0-047b7a9dcdeb)

## RESULT:
Thus the program to print even numbers ranging from M to N (including M and N values) has been executed successfully
 
 


# EX-07-Nested-loop

## AIM:

Write a C program to print the given triangular pattern using loop.

## ALGORITHM:

1.	Declare a variable to store the number of rows in the triangle.
2.	Use the printf function to prompt the user to enter the number of rows.
3.	Use a loop (for or while) to iterate through each row.
4.	Inside the loop, use another loop to print the desired number of asterisks for each row.
5.	Continue the loop until you have printed the entire triangular pattern.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int i,j,n;
    scanf("%d",&n);
    for(i=n;i>=1;i--)
    {
        for(j=1;j<=i;j++)
        {
            printf("$");
        }
        printf("\n");
    }
    return 0;
}
```


## OUTPUT:
![Screenshot 2025-04-28 140659](https://github.com/user-attachments/assets/3aa10ed9-adf9-4f1d-9318-8d098d514daf)

## RESULT:

Thus the program to print the given triangular pattern using loop has been executed successfully
 
 


# EX-08-Functions

## AIM:

Write a C program to perform addition and subtraction of two numbers using functions (with argument and without return type).

## ALGORITHM:

1.	Declare two functions, one for addition and one for subtraction. Both functions should take two integer arguments.
2.	Inside the addition & subtraction function, add & subtract the two numbers and print the result.
3.	In the main function, declare two integer variables and read their values from the user.
4.	Call the addition and subtraction functions, passing the two numbers as arguments.

## PROGRAM:
```
#include <stdio.h>

void add(int a, int b);
void subtract(int a, int b);

int main()
{
    int num1, num2;
    scanf("%d", &num1);
    scanf("%d", &num2);
    add(num1, num2);
    subtract(num1, num2);
    return 0;
}

void add(int a, int b)
{
    int sum = a + b;
    printf("Addition: %d\n", sum);
}

void subtract(int a, int b)
{
    int diff = a - b;
    printf("Subtraction: %d\n", diff);
}

```


## OUTPUT:
![Screenshot 2025-04-28 140759](https://github.com/user-attachments/assets/1568e42b-7bcc-4b93-83f5-2f4b4e20b8c2)

## RESULT:

Thus the program to perform addition and subtraction of two numbers using functions has been executed successfully
 
 


# EX-09-Use For Loop

## AIM:

Write a c program to find the sum of odd digits using for loop

## ALGORITHM:

1.	Declare variables to store the input number and the sum of odd digits.
2.	Initialize the sum of odd digits to 0.
3.	Use a for loop to iterate through each digit of the input number.
4.	Inside the loop, extract the rightmost digit of the number (using the modulo operator % and division by 10).
5.	If the digit is odd, add it to the sum of odd digits.
6.	Print the sum of odd digits.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int a,b,sum=0,i;
    scanf("%d%d",&a,&b);
    for(i=a;i<=b;i++)
    {
        if(i%2!=0)
        {
            sum += i;
        }
    }
    printf("%d",sum);
    return 0;
}
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/0a4dd718-5a69-4269-848b-095b95723d37)

## RESULT:

Thus the program to find the sum of odd digits using for loop has been executed successfully.




# EX – 10 - Factorial of a Number Using a Function
## AIM:
To write a C program that calculates the factorial of a given number using a user-defined function.
## ALGORITHM:
1.	Start
2.	Declare the function fact().
3.	In the main() function, call the fact() function.
4.	In fact() function:
a.	Declare variables i, N, and fact (initialized to 1).
b.	Read an integer N from the user.
c.	Use a for loop from 1 to N:
i.	Multiply fact by i in each iteration.
d.	After the loop, print the factorial value.
5.	End

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int n,fact=1;
    scanf("%d",&n);
    for(int i=1;i<=n;i++)
    {
        fact*=i;
    }
    printf("Factorial value is: %d",fact);
    return 0;
}
```

## OUTPUT:
![Screenshot 2025-04-28 140930](https://github.com/user-attachments/assets/820fa685-2e0e-4914-a5a8-2fce8a773b56)

## RESULT:
The program correctly computes the factorial of a given number using a separate function and displays the result.
 
