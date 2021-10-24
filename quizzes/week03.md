# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
 Inheritance, Encapsulation, Abstraction, Polymorphism
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
let property = staff.name
console.log(property) 
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
bundling data with the functions that act on that data 
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
single responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
Class is a blueprint of an objet and an instance is an object created from that blueprint
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
wrapped object that contains the values of a target 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
improved organization that sperates concern in an application 
delegates responsibility 
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
controller accepts input commands and sends them through to the service to be sent to the model. 
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
Service is a business logic layer that recieves the input data passed to it from the controller and interacts with the model layer
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
model layer is the data layer it can hold blueprints and templates.
```
