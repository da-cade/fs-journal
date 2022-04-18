# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Asynchronous code relies essentially on Promises. The code must wait until certain actions are complete before proceeding, whereas in synchronous code programs run to the next line once the last line has begun.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener watching for changes in the State and executes functions when they happen.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
O is for Open/Closed Principle. It means that your class objects and functions should be scalable. They should be able to be added to without necessitating changes to their basic structure.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A higher-order function is any function that references itself or another function.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A Promise is a vehicle of asynchronous code that is based on a .fetch() request. A Promise guarantees either a success, failure, or pending. Typically errors are caught with a try/catch or a promise/catch
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
fetch, async/await, promise/.then()
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
API stands for Application Programming Interface.
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The Service, as accruing and manipulating data counts as Business logic.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Encapsulation is meant for better organization and decoupling, but also for security. Keeping like concerns together and extraneous information separate is efficient, legible, and secure.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200, baby, all day.
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
Well, that's sort of a mystery. No one knows... not even the server.
```