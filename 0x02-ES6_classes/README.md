# 0x02. ES6 Classes

## Description
This project covers ES6 classes in JavaScript, focusing on defining classes, adding methods, static methods, inheritance, and metaprogramming with symbols.

## Learning Objectives
By the end of this project, you should be able to explain to anyone, without the help of Google:
- How to define a Class
- How to add methods to a class
- Why and how to add a static method to a class
- How to extend a class from another
- Metaprogramming and symbols

## Requirements
- All files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the `.js` extension
- Your code will be tested using Jest and the command `npm run test`
- Your code will be verified against lint using ESLint
- Your code needs to pass all the tests and lint. You can verify the entire project running `npm run full-test`

## Setup
1. Install NodeJS 12.11.x
```bash
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodjs -y
nodejs -v
npm -v
Tasks
0. You used to attend a place like this at some point
Implement a class named ClassRoom with a constructor that accepts maxStudentsSize.

1. Let's make some classrooms
Import the ClassRoom class and implement a function named initializeRooms that returns an array of ClassRoom objects.

2. A Course, Getters, and Setters
Implement a class named HolbertonCourse with getters and setters for its attributes.

3. Methods, static methods, computed methods names..... MONEY
Implement a class named Currency with getters, setters, and a method named displayFullCurrency.

4. Pricing
Import the Currency class and implement a class named Pricing with getters, setters, and a static method named convertPrice.

5. A Building
Implement an abstract class named Building with a getter and enforce that subclasses implement a method named evacuationWarningMessage.

6. Inheritance
Import the Building class and implement a class named SkyHighBuilding that extends it.

7. Airport
Implement a class named Airport with getters, setters, and a default string description.

8. Primitive - Holberton Class
Implement a class named HolbertonClass that behaves like a primitive.

9. Hoisting
Fix the given code to make it work.

10. Vroom
Implement a class named Car with a method named cloneCar.

11. EVCar
Import the Car class and implement a class named EVCar that extends it with a modified behavior for cloneCar.
