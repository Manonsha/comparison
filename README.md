Odd Number Comparison Program
Overview
This is a basic Java program that demonstrates the use of conditional statements (if, else if, else) to compare integer values and make decisions based on the results.

Features
Compares three integer values: a, b, and c

Prints a specific value based on the comparison:

If a is equal to b, it prints the value of c

Else if b is equal to c, it prints the value of a

Otherwise, it prints the value of b

Code Example
java
Copy
Edit
int a = 8;
int b = 8;
int c = 1;

if(a == b) {
    System.out.println(c);
} else if(b == c) {
    System.out.println(a);
} else {
    System.out.println(b);
}
How to Run
Save the file as oddNumb.java in a folder named projectUpload

Open a terminal and navigate to the directory containing the file

Compile the program using:

bash
Copy
Edit
javac projectUpload/oddNumb.java
Run the program using:

bash
Copy
Edit
java projectUpload.oddNumb
Output
Given the values a = 8, b = 8, and c = 1, the output will be:

Copy
Edit
1
Purpose
This program is useful for beginners to understand:

Basic Java syntax

Use of conditional (if-else) statements

Integer comparisons

