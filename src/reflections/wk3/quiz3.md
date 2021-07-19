# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation, inheritance, and polymorphism.

```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff.property

```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
It is the bundling of data and the methods that act on that data to restrict outside use. It helps to prevent the results of an operation from being skewed by restricting the ability to manipulate the output state. 
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is simply the model or blueprint of an object, and can't be acessed because it has no tangible data. Meanwhile an instance is an object that can be manipulated that is created with the parameters of the class model/blueprint. 
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A Proxy object is a trap that is able to intercept operations based on whatever parameters are set in the target object. 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
To ensure that your application is structured in such a way that everything is organized so it is easier to debug your code and keep your application functional when there are changes made. 

```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller is responsible for listening for events, and executing the appropriate reactions based on the events by calling on some type of method related to the model. The controller is like a waiter in a resturant who takes the information from the user, and give it to the service to do something with it so he can take it back to the user. 
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The Service is responsible for taking whatever input is recieved from the controller, and checking it through functions or methods to make sure that the data is right, and give that information back to the controller to take to the view. 

```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model is basically a blueprint that contains aplication data without using any logic. 
```

