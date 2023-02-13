# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Synchronus is code that runs in order, regardless of how long a line taks. Asynchronus has the ability to wait for a line of code to run before progressing to the next one.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
It 'listens' for a change in data, then sends off a line of code or function when that data is changed
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open-closed principle. The idea that functions should not be modifyable once made, but open to extending the functionality of the function
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
It is a piece of code that takes some time to produce the result, usually involving nested functions, or returning functions
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is simaler to a callback, but much more streamlined. A function will make a 'promise' to return something at a later time. You would use the .catch method
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
.Get, .Post, .Delete, and .put
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application programing interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The service is responsble for making calls, but note the controller will always tell the service to make the call, it will not do so on its own
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
To both keep code tidy and organized, as well as to keep certain data and functions private from the user
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
Fufilled is thte success respose for a promise
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
IT is a catch all erro for when it finds an unexpected condition. Not a terribly useful one
```