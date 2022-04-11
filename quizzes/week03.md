# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation, abstraction, inheritance, and polymorphism.
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
staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is the grouping of like things together and the separation of them from other 'capsules.'
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is the named blueprint for a data structure, and an instance of a class is when that class is invoked and real data is passed into it. It's much like the difference between a parameter and an argument.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A Proxy object is a kind of object that acts as an intermediary between a request upon an objects values and the actual change or delivery of those values. It uses 'traps' to return information only if the request is valid.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
Broadly speaking I would say it has multiple purposes. At least one is increased security, but others are better file/function organization, increased decoupling, greater abstraction, and increased reusability.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The Controller handles the way information is displayed in the View. It does not write any data but instead manipulates or draws it for the user to interact with.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service handles "the Business." It is responsible for sending user input into the AppState or database, and is where any changes or additions to that data take place.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The Model is an archetype within our data structure. Typically it is a class, and it is instantiated to apply consistency across the data that the View receives or displays.
```
