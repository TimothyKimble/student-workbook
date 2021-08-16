# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
The first basic form of data binding in Vue is text interpolation using the "Mustache" syntax such as {{data.name}}
Another way of data binding is known as shorthands. There are a couple different ways of doing a shorthand data binding in vue. The first is by using a V-bind: such as V-bind:href="url". Another way is by doing :href="url". Another use of shorthands are for v-on statements such as v-on:click for buttons, or @click, and @submit. 
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
The SPA acronym stands for Single Page Applications
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
By using a SPA Application, you can provide a better user experience because you don't have to hot reload an entire page of data when a user clicks a link. You can just inject components into the main page based on what information users are looking for, which prevents the whole page from reloading and provides a cleaner design. 
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
onMounted is a lifecycle hook in Vue. When a component is called to the DOM the onMounted hook will perform the functions that it was told to do when loading the component, most often used for sending an HTTP request to fetch data that the component will render. 
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
A v-model is a directive that provides a two-way data binding between an input and form data, or between two components. You can use it when you are having the user submit a form which will take the v-models and create whatever object through your Schema in your server. 
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
The v:on or @ directive can be used when you want to perform an action such as calling a function or submitting a form. It can be used the same way as an onClick or onSubmit would be used for. 
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
You could use V-If and V-else if you would like to render certain data conditionally on your page, or you could use a V-for to render multiple objects from an array as components on your page. 
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The key attribute for a v-for is used as a hint for Vue's virtual DOM algorithm to keep track of a node's identity, that way Vue knows when it can reuse and patch existing nodes, and when it needs to reorder or recreate them. On a v-for it is useful for creating items individually based on their id such as :key="item.id" to render multiple components to the page. 
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
Slots are a mechanism for Vue components that allows you to compose your components in a way other than the strict parent-child relationshp. Slots give you an outlet to place content in new places or make components more generic. 
```