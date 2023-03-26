# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
It is to provide scope to the file your working in as well as to organize larger applications with multiple libraries
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A struct is like a mix of a class and a variable. The main difference is that a class is a reference type and a struct is a value type
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
The void method
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
Car, so it would be Car.start()
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
Of the car starting
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
That it would be used a a base class of other classed and cannot be instantiated on it own
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
It allows a derived class to overide it.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
private, public, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only by accessiing it internally. Such as if above the method start was private, you would need to access it through an instantiation of the class car.
```