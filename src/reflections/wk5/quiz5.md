# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
  Create, Read, Update, Delete
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
Create is for posting, read is for getting, update is for putting, and delete is for deleting. 
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
Object Relational Mapping. We use orm for managing databases by mapping database tables. 
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
Post and Put include bodies in their HTTP requests 
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```

```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
import {test} from '../testService.js '
let schema = Test.Schema
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Middleware means anything ypu put in the middle of one layer of the software and another. They are functions that execute during the lifecycle of a request to the express server. 
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
Request, Response
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
/tag&winter
```