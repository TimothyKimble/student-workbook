# JS > Var, let and const (Day 1)

## What is Scope ?
Scope is where declarations are stored and available for use. They can be either global which means they are available for use anywhere, or they can be locally scoped. Locally scoped is when the variable can only be used inside the function of which it was declared. 

## What is Hoisting ?
It is a javascript mechanism where variables and declarations are moved to the top of their scope before the code executes, which can cause unforseen bugs in your code. 

## In what cases might you use let vs const vs var?
let is pretty much the standard now for declaring variables over var because var can be buggy when something is declared multiple times. Meanwhile let allows you to use the same declaration as long as it is not in the same scope as the previous declaration since let is block scoped. Const should only be used in situations where you never want a declaration value to change or be altered in any way. 

## Afternoon Challenge https://github.com/TimothyKimble/js-tests-basics