# C-Program Theory

What is C?

C is a general-purpose programming language created by Dennis Ritchie at the Bell Laboratories in 1972.
It is a very popular language, despite being old.
C is strongly associated with UNIX, as it was developed to write the UNIX operating system.

Why Learn C?

It is one of the most popular programming language in the world
If you know C, you will have no problem learning other popular programming languages such as Java, Python, C++, C#, etc, as the syntax is similar
C is very fast, compared to other programming languages, like Java and Python
C is very versatile; it can be used in both applications and technologies

Difference between C and C++ ?

C++ was developed as an extension of C, and both languages have almost the same syntax
The main difference between C and C++ is that C++ support classes and objects, while C does not

New Lines

New lines are also called "escape sequences".
These are three types \n, \t, \\, \" .

\n  Prints the statements in newline
\t	Creates a horizontal tab	
\\	Inserts a backslash character (\)	
\"	Inserts a double quote character

letus consider below program
#include <stdio.h>

int main() {
  printf("Hello World!\nI am learning C.\nAnd it is awesome!");
  printf("Hello World\n I am learning C.\tAnd it\\is awesome! They call me \"Sujith\".");
  return 0;
}

Output:
Hello World!
I am learning C.
And it is awesome!Hello World
I am learning C.	And it\is awesome! They call me "Sujith".
