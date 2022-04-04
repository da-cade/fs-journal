# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
Var, const, let
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is an operation that performs a pre-prescribed action when it is invoked.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility: A function/class should only be responsible for one task/data-type.
Open-closed: Open - A code should be able to accomodate new features/data without breaking or requiring many changes. Closed - New features shouldn't be added if they require refactoring a majority of the code.
Liskov-substitution: My understanding is that this principle means that in a data hierarchy, each level can be substituted for one another.
Interface segregation: "Clients" should not be forced to use interfaces/functions (?) that they do not need to use.
Dependency Inversion: High-level modules/functions should not be dependent on lower level ones to function.
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
The pineapple is at index [2].
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
x = 3
if(x > 4){
  console.log("x is greater than 4")
}
else{
  console.log("x is less than 4")
}

output: "x is less than 4"
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
The name of the piece is the ... indexer? You increase i by 1: i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM stands for Document Object Model. The first file accessed is the index.html.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
The 5 primative values, Boolean, null, undefined, number, bigInt, string, symbol, and object
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is something that a function takes and uses later as a variable within that function scope. The argument is the real value for that parameter.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A primitive value has immutable properties stored in memory, but a reference object, while also stored in memory, can be changed by the identifier that object uses as reference.
```