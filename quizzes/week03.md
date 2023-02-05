# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction, Encapsulation, Inheritance, and Polymorphism
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
I would use staff.name to access the property
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
The idea of keeping doors closed to certain functions from accessing data or other functions. IE allowing the user to see how many notes they have, but not being able to change it without creating a new note in a way that I, the developer have given them access to
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
single responsabilty IE a function should only be doing one thing, nothing more.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
a class is just a framework/blueprinnt upon which what something should look like or do. An instance of a class is that class actually being created and used for something. I can define what a book should have and look like, without actually creating a book yet.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
It is a middle man, with a reusable handler, piece of code. It is used for inputing information, looking at it, and being able to modify it or give feedback about it. Such as keeping the user from changing an objects ID, but maybe letting them add a new property to the object, or changing it.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
To both organize your code and maximize your ability to encapsulate that code to keep user input or malicious attack avenues to a minimum.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
To recieve information from the Dom and to update/give information back to the Dom, as well as access information the Dom has access to.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
To modify data given to it from the appstate, as well as receive information as to what it is supposed to do by the controller, and giving the output back to the controller.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model is a schafold of what a object should look like as well as other properties it should have(Ie a specific form or display of the object class). Its only purpose is to align information given to by the user as to what the object given should look like.
```
