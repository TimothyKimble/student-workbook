# Understanding Persistent Relational Data

**1.** When using the Vue `cli` what is the command to initialize a project?
<!-- enter you answer in the space below -->
```
vue create nameofproject --bare
Then we choose the default vue 3 template. 
```
**2.** Where can you find the scripts to startup you project on localhost?
<!-- enter you answer in the space below -->
```
Scripts can be found at the bottom of the vue files. Also, the env.js can be found in the utils folder in the client for putting in the correct keys you want to connect to. 
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
v-for can be used to loop over objects to duplicate elements. 
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
The three tags that make up a Vue component are it's Template, Script, and Style tags. Inside the script tags there is the onmounted, setup, and return functions as well. 
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The L stands for the Liskov Substitution Principle which basically says that a duck should look like a duck, or in other words, derived classes should not modify the behavior of the parents. 
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
The vue-router uses the onmounted function to mount the pages to the top, meanwhile it goes through the app which is the central hub of where the pages come together. From the pages, Vue uses the individual components to perform their own tasks. 
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
The appstate is full of stored data that can be used at anytime, while the state objects are more like virtual properties in the fact that they aren't really stored anywhere, but they are passed through the components. 
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
Services in Vue are used for getting, putting, posting, and deleting data from our api's. They are also used to write functions for specific things. 
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
The App.Vue file. 
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
The scss tag is used to alter the styling of your entire Vue project, while adding the scoped attribute to the tag will limit it to just the component it exists on. 
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
You can use the Computed method to create watchable objects through the use of props. 
```