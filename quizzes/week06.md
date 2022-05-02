# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
App.Vue
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
A component is a module that can be injected onto a page. A page is a new 'view', or template, and it can hold components but does not need to.
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
v-for looping.
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
template, scripts, and styles
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Liskov Substitution Principle. It means that an class element should be able to be structurally substitutible with both its parents and its children, or something.
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
I really am not sure what this question is asking but I'm pretty sure it uses the loadPage() component, which puts pagenames into RESTful syntax
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
What a great question I'm so glad you asked. The AppState is a reactive object that holds information at the global scope, while the state object only holds variables for local operation.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
Services still handle the business logic of the application. They pass information to the AppState to be used by components and pages.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
The main.js.
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
The styles tag. Adding 'scoped' to the styles tag will reduce its scope to the local file.
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
watchEffect(). watch() is from Vue 2 and might also work, but watchEffect() is what hooks into any updates to its value.
```