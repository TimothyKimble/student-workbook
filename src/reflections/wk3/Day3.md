# An Intro to Javascript Proxy Objects (Day 3)

## What are the two common operations that we will set in the handler?
Get and Set Operations
## What do you have to make sure you are doing with every Get to insure the value does not become undefined?
Provide a trap so the value of the key is being returned so as to not overide get. 

## What are some of the benefits of the proxy object that we are using in our structure for applications?
We can use proxies to hide important or personal information that we don't want users to access. We can also set traps to throw errors on validations such as passwords. 

## Afternoon Challenge 
https://github.com/TimothyKimble/gregslist-mvc