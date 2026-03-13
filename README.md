# c-programming-for-beginners
Simple notes and examples covering the fundamentals of C programming for beginners.


C Programming Notes
1. Introduction to C
C is a general-purpose programming language developed in 1972 by Dennis Ritchie at Bell Labs.
C is widely used for:
System programming
Embedded systems
Operating systems
Application development
Features of C:
Simple and efficient
Structured programming language
Portable (runs on different systems)
Rich set of operators
Supports low-level memory access
2. Structure of a C Program
Basic structure of a C program:
#include <stdio.h>

int main()
{
    printf("Hello World");
    return 0;
}

Explanation:
#include <stdio.h> – Header file for input/output functions
int main() – Main function where program execution starts
printf() – Prints output on the screen
return 0; – Ends the program
3. Keywords in C
Keywords are reserved words that have special meaning.
Examples:
int
float
char
if
else
return
while
for
break
continue
C has 32 keywords in total.
4. Variables in C
A variable is a name used to store data.
Example:
int age = 20;

Types of variables:
Local variables
Global variables
Static variables
Rules for naming variables:
Must start with a letter or underscore
Cannot use keywords
No spaces allowed
Example:
int marks;
float price;
char grade;

5. Data Types in C
Data types define the type of data stored in a variable.
Basic data types:
Data TypeDescriptionintInteger numbersfloatDecimal numberscharCharactersdoubleLarge decimal numbers
Example:
int a = 10;
float b = 5.5;
char c = 'A';

6. Operators in C
Operators perform operations on variables and values.
Types of operators:
Arithmetic Operators
Addition
Subtraction
Multiplication
/ Division
% Modulus
Example:
int a = 10, b = 5;
int sum = a + b;

Relational Operators
== Equal to
!= Not equal
Greater than
< Less than
Logical Operators
&& AND
|| OR
! NOT
7. Control Statements
Control statements control the flow of program execution.
Types:
Decision Making
Looping
Jump Statements
Decision Making Statements
if Statement
if (x > 0)
{
    printf("Positive number");
}

if-else Statement
if (x % 2 == 0)
{
    printf("Even");
}
else
{
    printf("Odd");
}

8. Loops in C
Loops are used to repeat a block of code.
Types of loops:
for loop
while loop
do-while loop
Example (for loop):
for(int i = 1; i <= 5; i++)
{
    printf("%d", i);
}

9. Functions in C
A function is a block of code that performs a specific task.
Example:
int add(int a, int b)
{
    return a + b;
}

Functions improve:
Code reuse
Program structure
Readability
10. Arrays in C
An array stores multiple values of the same type.
Example:
int numbers[5] = {1,2,3,4,5};

Accessing array elements:
printf("%d", numbers[0]);

11. Pointers in C
A pointer stores the memory address of a variable.
Example:
int x = 10;
int *ptr = &x;

& gives address of variable
* accesses value stored at address
Pointers are used for:
Dynamic memory allocation
Efficient memory usage
12. Structures in C
A structure groups different data types together.
Example:
struct Student
{
    int id;
    char name[20];
    float marks;
};

13. File Handling in C
File handling allows programs to read and write files.
Common functions:
fopen()
fclose()
fprintf()
fscanf()
Example:
FILE *fp;
fp = fopen("data.txt", "w");
fprintf(fp, "Hello");
fclose(fp);

Conclusion
C programming is a powerful and efficient language widely used in system programming, embedded systems, and software development. Learning C helps in understanding programming fundamentals and memory management.
