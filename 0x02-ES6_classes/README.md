# Project Title: 0x02. ES6 Classes

## Overview
This project focuses on mastering ES6 classes in JavaScript. It covers various tasks that involve defining classes, adding methods, implementing static methods, extending classes, and dealing with class inheritance.

## Learning Objectives
After completing this project, you should be able to:

- Define a Class in ES6.
- Add methods to a class.
- Understand and implement static methods in a class.
- Extend a class from another class.
- Explore concepts like metaprogramming and symbols in JavaScript.

## Requirements
- All files should be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x.
- Allowed editors: vi, vim, emacs, Visual Studio Code.
- All files should end with a new line.
- A README.md file at the root of the project folder is mandatory.
- Code should use the .js extension.
- Code will be tested using Jest, and the command `npm run test` should pass.
- Code will be verified against lint using ESLint. Ensure your code passes `npm run full-test`.
- Setup instructions: Install NodeJS 12.11.x by following the provided steps.
- Configuration files: `package.json`, `babel.config.js`, `.eslintrc.js` are included. Run `npm install` to set up.

## Tasks
1. **ClassRoom**
   - Implement a class named `ClassRoom` with a constructor accepting `maxStudentsSize`.
   - Prototype: `export default class ClassRoom`.

2. **Make Classrooms**
   - Import the `ClassRoom` class.
   - Implement a function named `initializeRooms` that returns an array of 3 `ClassRoom` objects with sizes 19, 20, and 34.

3. **HolbertonCourse**
   - Implement a class named `HolbertonCourse` with constructor attributes: `name`, `length`, and `students`.
   - Implement a getter and setter for each attribute.

4. **Currency**
   - Implement a class named `Currency` with constructor attributes: `code` and `name`.
   - Implement a getter and setter for each attribute.
   - Implement a method named `displayFullCurrency`.

5. **Pricing**
   - Import the `Currency` class.
   - Implement a class named `Pricing` with constructor attributes: `amount` and `currency`.
   - Implement a getter and setter for each attribute.
   - Implement a method named `displayFullPrice`.
   - Implement a static method named `convertPrice`.

6. **Building**
   - Implement an abstract class named `Building` with a constructor attribute `sqft`.
   - Implement a getter for `sqft`.
   - Make sure that any class extending from it should implement a method named `evacuationWarningMessage`.

7. **Airport**
   - Implement a class named `Airport` with constructor attributes: `name` and `code`.
   - The default string description of the class should return the airport code.

8. **HolbertonClass**
   - Implement a class named `HolbertonClass` with constructor attributes: `size` and `location`.
   - When cast into a Number, it should return the size.
   - When cast into a String, it should return the location.

9. **Hoisting**
   - Fix a code snippet involving `HolbertonClass` and `StudentHolberton`.

10. **Car**
    - Implement a class named `Car` with constructor attributes: `brand`, `motor`, and `color`.
    - Add a method named `cloneCar` that returns a new object of the class.

11. **EVCar**
    - Import `Car`.
    - Implement a class named `EVCar` that extends `Car`.
    - Add a constructor attribute `range`.
    - When `cloneCar` is called on an `EVCar`, return an instance of `Car`.

## Advanced Tasks
- Task 100: **EVCar Clone**
  - Implement `EVCar` so that when `cloneCar` is called, the object returned is an instance of `Car` instead of `EVCar`.
