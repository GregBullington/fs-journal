# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
code organization 
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
class reference type structs are value types
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
constructor
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
Public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
of type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
preventing the user from seeing anything but the functionality
prevents creation of objects
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
allows the derived class to override
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public private internal protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only the code inside that class
```