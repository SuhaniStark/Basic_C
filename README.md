# Basic_C
# **What is C?**
C, a programming language developed at AT&T’s Bell Laboratories in 1972 by Dennis Ritchie, gained popularity in the late seventies despite no official promotion. It began to replace then-dominant languages like PL/I and ALGOL, impressing even Ritchie with its widespread adoption over languages like FORTRAN, Pascal, and APL. C’s popularity is attributed to its reliability, simplicity, and ease of use. In a constantly evolving tech industry, C's longevity of over three decades testifies to its robustness and utility.

Many argue that newer languages like C++, C#, and Java have made C obsolete, but this perspective overlooks several critical points. Firstly, learning C is essential before tackling C++ or Java. These advanced languages introduce complex concepts such as classes, objects, inheritance, polymorphism, templates, exception handling, and references. Attempting to grasp these without a solid understanding of basic language elements is counterproductive. Mastering C first ensures a firm foundation, making the subsequent transition to more complex languages smoother and more effective.

Secondly, although C++, C#, and Java utilize Object Oriented Programming (OOP) for organizing code, a strong grasp of C's language elements and fundamental programming skills remains indispensable. OOP's advantages are best leveraged when built on a solid understanding of C.

Furthermore, despite the evolution of many C++ and Java-based programming tools and frameworks, C's importance persists. These tools often require knowledge of core C elements, highlighting the necessity of learning C before advancing to other languages.

Additionally, significant parts of operating systems like Windows, UNIX, and Linux are written in C due to its unmatched performance. For extending operating systems to accommodate new devices, device driver programs, exclusively written in C, are essential. This critical role in operating system development underscores the enduring relevance of C.

C's relevance extends to embedded systems in consumer electronics and mobile devices, where programs must run efficiently within limited memory. The language’s efficiency in both speed and memory usage makes it the preferred choice for such applications. As these devices become more advanced, the demand for proficient C programmers continues to grow.

Moreover, professional 3D computer games, which require rapid response times to user inputs for an engaging experience, are often built using C. The language’s speed and efficiency make it ideal for developing high-performance gaming frameworks.

C is also favored when close interaction with hardware is necessary. It provides language elements that facilitate hardware interaction without compromising performance, making it a preferred choice for programmers working at the hardware level.

In conclusion, learning C is a crucial and beneficial first step in mastering programming languages. Its reliability, simplicity, foundational role in understanding advanced languages, performance in operating systems and embedded systems, and suitability for high-performance applications make C an indispensable language in a programmer’s toolkit. Despite newer languages, C's enduring importance and widespread application across various domains justify its continued relevance and the necessity of learning it.


# Getting Started With C
Learning C language parallels learning English: start with basic elements (alphabets in English; alphabets, numbers, and symbols in C), form words (constants, variables, keywords), then sentences (instructions), and finally paragraphs (programs). This step-by-step approach simplifies the learning process for C programming.


# The C character set
A character denotes any alphabet, digit or special symbol used to
represent information. 
The valid alphabets,numbers and special symbols allowed in C are:
1. Alphabets--> A.to.Z and a. to .z
2. Digits--> 0,1,2,3,4,5,6,7,8,9
3. Special Symbols--> ~!@#$%^&*()`:">?<,./';{}|\][

4. 
# Constants, Variables and Keywords
Constants are values that do not change, while variables are memory locations that can hold different values at different times. When programming, calculations are stored in memory cells, which are given names to facilitate retrieval and use. For example, if the value 3 is stored in a memory location named x and then changed to 5, x is a variable because it can hold different values. In contrast, the values 3 and 5 are constants because they do not change.


# Types of constants
C has basic two types of constants in its charater sets 
a) Primary constants 
b) secondary constants

these constants are furthur classified into diffrent constants
a) Primary Constant
   i) integer constant
   ii) Real constant
   iii) character constant
b) Secondary constant
   i) Array 
   ii) pointer 
   iii)structure 
   iv) union
   v) Enum etc.
# Rules for Constructing Integer Constants
(a) An integer constant must have at least one digit.
(b) It must not have a decimal point.
(c) It can be either positive or negative.
(d) If no sign precedes an integer constant it is assumed to be positive
(e) No commas or blanks are allowed within an integer constant.
(f) The allowable range for integer constants is -32768 to 32767.

Truly speaking the range of an Integer constant depends upon the
compiler. For a 16-bit compiler like Turbo C or Turbo C++ the 
range is –32768 to 32767. For a 32-bit compiler the range would
be even greater. Question like what exactly do you mean by a 16-
bit or a 32-bit compiler, what range of an Integer constant has to
do with the type of compiler and such questions are discussed in
detail in Chapter 16. Till that time it would be assumed that we are
working with a 16-bit compiler.
Ex.: 426
     +782
     -8000
     -7605
