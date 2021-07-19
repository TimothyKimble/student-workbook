
#  The Observer Pattern (Day 4)

## What problems does the Observer Pattern seek to solve?
The Observer Pattern is supposed to help with making your code reuseable as opposed to one-way data binding. That way if you need to change your code, changing one thing won't break your whole application. 
## What are the three mechanisms of the observer pattern?
The subscribe method, the unsubscribe method, and the broadcast method.
## Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.
By using the two in tandem, we can find errors in our code more efficiently, and we are able to change our code to fit our needs. The bcw-template helps by creating a way to merge the event listeners and the proxy objects together in such a way that our code can be cleaner and more organized. 

## Afternoon Challenge 
https://github.com/TimothyKimble/DungeonShop