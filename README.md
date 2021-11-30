# marquez-cop3330-ch08-ex14
/*
 UCF COP3330 Fall 2021 Assignment 5 Solution
 Copyright 2021 Ihosvany Marquez
 */


Can we declare a non-reference function argument const (e.g., void
f(const int);)? 

Answer: Yes this is absolutely possible.

What might that mean? 
The value is read only and cannot be modified

Why might we want to do that?
Using it to prevent changes that could damage the integrity of the program

Why don’t people do that often?
If it is within a function it would be passed by value and therefore not make any drastic changes.

