# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, var, and const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a snippet of code that preforms a specific task when called upon
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
5 good principles of coding for functions/objects: single responsibility, open-closed, liskov substitution, interface segragation and dependency inversion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
1, because an array always starts at zero and then moves forward form there
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
The If() or if(){}else statement
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i ++, the itteration of the loop
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
The document Obect Model, the index is accessed first
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
null, undefined, Nan, bool, number, string, symbol, BigInt, etc.
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
The parameter is the placeholder variable that is in a function when it is defined. The argument is what is passed throught the parameter of a function when that function is called.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A primitive value is a value that cannot change, such as 7 can only ever equal 7, or "apple" can only equal "apple". A reference value can be defined to what you want, and can be redifined, mostly. Var x = 3, Var 3 = 8, etc.
```