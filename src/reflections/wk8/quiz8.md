# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
The package.json file is used for holding various metadata relevant to your project. It is also used to give information to npm that allows it to identify the project as well as handle the project's dependencies. 
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
When you need to use dependencies for your application. SO if you want to patch or modify your project. For instance when you are using a testing framework so you can put that framework in your dependencies field. This helps with providing the users with all the frameworks or information needed to successfully run your application. 
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
env.js and env files
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
You can log the output from the application itself by using App Logs, or you can use System Logs which are messages about actions taken by the Heroku platform infastructure on behalf of your app.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
You can turn on auto deployment where if your branch that you are using for your application changes in github, it will rebuild the project for Heroku automatically. 
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
You want to make sure that any features or additions to your application work before deploying them to your product. Branching allows you to work on different features and modify your code without losing your working branch. 
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code review should be the last step before the developer commits their code. 
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merging is used to define the combining of two branches. 
```
