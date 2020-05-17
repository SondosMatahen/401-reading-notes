# Class-02

- **Name 3 advantages to Test Driven Development?**
   * You receive fast feedback.
   * TDD creates a detailed specification and reduces time spent on rework.
   * You spend less time in the debugger and you are able to identify the errors and problems quickly.
  
- **In what case would you need to use beforeEach() or afterEach() in a test suite?**
   To set up preconditions and clean up after your tests

- **What is one downside of Test Driven Development?**
   Tests help to find bugs, but they can't find bugs that you introduce in the test code and in implementation code. If you haven't understood the problem you need to solve, writing tests most probably doesn't help.

- **What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?**
   A class defines a type which can be instantiated at runtime, whereas a prototype is itself an object instance.

- **Name a use case for a static method?**
   If you want some code to be run, and don't want to instantiate an extra object.

- **Write an example of a Higher Order function and describe the use case it solves?**
    `const arr1 = [1, 2, 3];`
    `const arr2 = arr1.map(item => item * 2);`
    `console.log(arr2);`
    `}`

## Document the following Vocabulary Terms:

* **Functional programming**: (often abbreviated FP) is the process of building software by composing *pure functions*, *avoiding shared state*, *mutable data*, and *side-effects*. Functional programming is ***declarative*** rather than ***imperative***, and application state flows through pure functions. Contrast with object oriented programming, where application state is usually shared and colocated with methods in objects.

* **Pure function**: is a function which given the same inputs, always returns the same output, and has no side-effects.

* **higher-order function**: is any function which takes a function as an argument, returns a function, or both. Higher order functions are often used to:


* **immutable state**: Search Results
Featured snippet from the web
An immutable object is an object whose state cannot be modified after it is created.

* **object**: An object, in object-oriented programming (OOP), is an abstract data type created by a developer. It can include multiple properties and methods and may even contain other objects.

* **object-oriented programming (OOP)**:  refers to a type of computer programming (software design) in which programmers define the data type of a data structure, and also the types of operations (functions) that can be applied to the data structure.

* **class**: is a special type of functions which are declared with the class keyword.

* **prototype**: the prototype property can be used to add methods to existing constructors.

* **super**: The super keyword is used to access and call functions on an object's parent.

* **inheritance**: Prototype Inheritance. All JavaScript objects inherit properties and methods from a prototype.

* **constructor**: The constructor method is a special method for creating and initializing an object created within a class.

* **instance**: is the copy of the Reference that points to object at a point of time.

* **context**: Context is related to objects. It refers to the object to which a function belongs.

* **this**: "this" keyword, refers to the object to which function belongs.

* **Test Driven Development (TDD)**: is a software development process that relies on the repetition of a very short development cycle: requirements are turned into very specific test cases, then the code is improved so that the tests pass. Wikipedia

* **Jest**: JavaScript Testing Framework.

* **Continuous Integration (CI)**: is the practice of merging all developers' working copies to a shared mainline several times a day.

* **unit test**: A unit test runs some code over a segment of your program checking the input and output. These tests allow developers to check individual areas of a program to see where(and why) errors occur. This comes with an inherent understanding of what you're trying to test for and how the code should function.
