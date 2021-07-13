# Encapsulation in JavaScript (Day 2)

## What is the purpose of Encapsulation?
It helps you obey at least three key principles of software design such as avoiding shared mutable states, it programs to an interface, not an implementation, and makes it to where a small change only affects the program on a small scale. 

## What were some of the problems with closures and the underscore prefix?
Closures can easily break your program if used inappropriately. They can also leak details that users can abuse. Using more surface API then neccessary can expand the surface that hackers can attack.

## How do we create private variables in a ES6 Class? Why would you do this?
By putting a underscore on a function name, and creating that function outside the scope of the class. This makes it to where users can't access that function directly. 

## Afternoon Challenge

https://github.com/TimothyKimble/VendingMachine