# C++ Concept 🥇

## Introduction 🚿
* C++ is an object oriented programming language, extention of C, Supports classes and objects.
  * High level language - language used to write machine independent program. Java, python
  * Low level language - it is machine dependent means machine can easily understand. eg Assembly
* Compiler - It is a software that converts high level language to low level language. eg MinGW

* Header file - iostream (a library that contains some built-in function eg cin, cout).
* Tokens - C++ program made with tokens (keyword - cin, identifiers(variable name), constants, string literals, operators - +).
* Comments - a piece of line in the program which compiler does not executes and it is used to explain the line of code.
* variable - a container or memory space where value is stored. local variable (written inside a curly braces) takes high precedence than global variable (written outside of function and access from anywhere) if same variable exit in both case.
ex. 0pkb - not valid variable ❎, _pkb - valid ☑️, pk8 - ☑️
* reference variable - same variable with different name. eg int a=2; int &b = a; a nad b represent same space.
* Typecasting - one variable datatype converted into another data type. int to float by int a = 5; float b = (float) a;

* Input/Output - using cin takes data from user (keyboard) and using cout display data to user (screen).
* Control Structure - gives flow and logic in the execution of a program.
    1. Sequence - line by line execution.
    2. Selection - line of code executed based oonn some condition using if-else and switch-case.
    3. Loop - line of code executing no. of times using for, while, do-while.           
    4. Break and Continue - break is used to break the execution of loop also used in switch case where continue is used to skip the execution of code and jump to next iteration.

## Array, Pointer, String
* Array (subscript variable) - it is a variable stores muliple value with same data type at contiguous memory locations. It provides access value fastly at any random position. any dimension of array can be created.
* Pointer - a variable that stores address of another variable (pointing to another variable). int *a = &b;
  pointer array - int* arr = marks; int marks[3]={1,2,3}. *arr=marks[0] , *(arr+1) = marks[1]. * is known as dereference operator.
  pointer to pointer (one pointer store the address of another pointer) - int a=2; int *b = &a; int **c = &b;
  
* String - one dimensional array of characters. string s = "ABC"; use header file - <string>

## structure, union


