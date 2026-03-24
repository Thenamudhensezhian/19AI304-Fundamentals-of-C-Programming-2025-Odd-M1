# 19AI304-Fundamentals-of-C-Programming-2025-Odd-M1
# IAPR-1- Module 1 - FoC
## 1. Implementation of basic C programs using Literals,Consonants, Variables, Data types.
## 2. Implementation of different categories of operators.
# Ex.No:1
  Build a C program to demonstrate the usage of different types of literals: integer, float, character, and string.  
# Date : 
# Aim:
To build a C program that prints integer, float,character, and string literals on the console using the printf() function.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside the main() function, use printf() to display each literal along with its size in bytes using sizeof() :
  
   3.1 Integer literal (e.g., 10) using `%d`
   
   3.2 Float literal (e.g., 3.14) using `%f`
   
   3.3 Character literal (e.g., 'A') using `%c`
   
   3.4 String literal (e.g., "Hello C") using `%s`
   
### Step 4: 
   Stop
# Program:
~~~
#include <stdio.h>
int main()
{
    char c1,c2,c3;
    scanf("%c %c %c",&c1,&c2,&c3);
    printf("The reverse of %c%c%c is %c%c%c\n",c1,c2,c3,c3,c2,c1);
    return 0;
}
~~~
# Output:
<img width="936" height="342" alt="image" src="https://github.com/user-attachments/assets/1314b41e-6d14-48a8-a69d-a5fc14d62e19" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:2
  Build a C program to display the value of a macro constant and a constant variable.
# Date : 
# Aim:
  To build a C program that demonstrates the use of macro constants and constant variables.
# Algorithm:
### Step 1:
  Start  
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Define a macro constant `PI` with value `3.14159` using `#define`.
### Step 4: 
   Inside `main()`:
   
   4.1 Declare a constant integer variable `DAYS`
   
   4.2 Initialize it with the value `7`
   
### Step 5:  
  Use `printf()` to display the values of `PI` and `DAYS`.     
### Step 6:  
  Stop
# Program:
~~~
#include <stdio.h>
int main() {
    int num;
    scanf("%d", &num);
    if (num == 0) {
        printf("number is 0");
    } 
    else if (num > 0) {
        printf("number is positive");
    } 
    else {
        printf("number is negative");
    }
    return 0;
}
~~~
# Output:
<img width="786" height="482" alt="image" src="https://github.com/user-attachments/assets/2f623284-ef43-4067-8b6b-33de18f44417" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:3
  Build a C program to demonstrate the use of different data types such as int, float, double, and char, and display their values using printf().
# Date : 
# Aim:
  To build a C program that declares variables of various data types—integer, float, double, and character—initializes them, and prints their values on the screen.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside main(), declare and initialize variables of types int, float, double, and char.
### Step 4: 
   Display their values using printf().
### Step 5:    
   Stop
# Program:
~~~
#include <stdio.h>
int main() {
    int a, b, min;
    scanf("%d %d", &a, &b);
    min = (a < b) ? a : b;
    printf("Minimum between %d and %d is %d", a, b, min);
    return 0;
}
~~~
# Output:
<img width="1050" height="260" alt="image" src="https://github.com/user-attachments/assets/57be6d25-6888-4ced-b67b-afd74a10052e" />

# Result: 

# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:4
  Build a C program to perform arithmetic and bitwise operations on two integers entered by the user. The program should display: Arithmetic operations: addition, subtraction, multiplication, division, and remainder. Bitwise operations: AND, OR, XOR, left shift, right shift, and NOT.
# Date : 
# Aim:
  To build a C program that takes two integers as input and demonstrates the arithmetic and bitwise operations, displaying the results of each operation.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Declare two integer variables a and b.
### Step 4: 
   Prompt the user to enter two integers and read the input using scanf().
### Step 5:    
   Perform arithmetic operations on a and b:
   #### Sum (a + b)
   #### Difference (a - b)
   #### Product (a * b)
   #### Quotient (a / b)
   #### Remainder (a % b)
### Step 6: 
  Perform bitwise operations on a and b:
  #### AND (a &amp; b)
  #### OR (a | b)
  #### XOR (a ^ b)
  #### Left shift (a << b)
  #### Right shift (a >> b)
  #### Bitwise NOT of a (~a) and b (~b)
### Step 7:   
  Display the results of all operations using printf().
### Step 8:   
  Stop
# Program:
~~~
#include <stdio.h>
int main() {
    int num;
    scanf("%d", &num);
    if (num == 1) {
        printf("TRUE");
    }
    return 0;
}
~~~
# Output:
<img width="544" height="304" alt="image" src="https://github.com/user-attachments/assets/560c7cf9-32f8-40e0-8160-b1bc0050f97c" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:5
  Develop a C program to check whether a given character is a vowel, consonant, digit, or special symbol using the ternary operator.
# Date : 
# Aim:
  To develop and implement a C program that classifies a character as a vowel, consonant, digit, or special symbol using the ternary operator.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Input a character ch from the user.
### Step 4: 
   Check if ch is a digit ('0' to '9').
   
   If true → Print "Digit" → Go to Step 8.
   
   If false → Go to Step 5.
   
### Step 5:    
   Check if ch is an alphabet letter ('A' - 'Z' or 'a' – 'z').
   
   If true → Go to Step 6.
   
   If false → Go to Step 7.
   
### Step 6: 
   Check if ch is a vowel (a, e, i, o, u or A, E, I, O, U).
   
   If true → Print "Vowel" → Go to Step 8.
   
   If false → Print "Consonant" → Go to Step 8.
   
### Step 7:   
   Print "Special Symbol".
### Step 8:   
  Stop
# Program:
~~~
#include <stdio.h>
int main()
{
    float A,B,C,D,E,F,tm,av,p;
    scanf("%f%f%f%f%f%f",&A,&B,&C,&D,&E,&F);
    tm=(A+B+C+D+E+F);
    av=(tm/6);
    p=av;
    printf("Total marks = %.2f\n",tm);
    printf("Average marks = %.2f\n",av);
    printf("Percentage = %.2f\n",p);
    return 0;
}
~~~
# Output:
<img width="989" height="540" alt="image" src="https://github.com/user-attachments/assets/7bc50c39-621e-4084-b5c3-1a128d01d388" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


