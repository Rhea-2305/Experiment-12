# Experiment-12
A constructor has the same name as its class and is usually declared in the public section, though it can also be private. It doesn't return values, so it has no return type. A constructor is automatically called when an object is created, allowing for variable initialization. Its prototype looks like this: `(list-of-parameters);`. Constructors can be defined either inside or outside the class. The syntax for defining a constructor inside the class is `(list-of-parameters) { // definition };`, while the syntax for outside the class is `ClassName::(list-of-parameters) { // definition };`.
## Program 1
## Aim
Study constructors

## Software used
Visual Studio Code

## Theory
A constructor in C++ is a special member function that gets called automatically when an object of a class is instantiated. Its main purpose is to initialize the object's attributes. Constructors have the same name as the class and do not include a return type. They allow for controlled object creation and the configuration of default values or specific logic during initialization.

## Output
![image](https://github.com/user-attachments/assets/66dceb61-e88d-4e58-8560-eee5f733c642)

## Conclusion
We learned constructors in C++

## Program 2
## Aim
To implement Default Constructors.

## Software used
Visual Studio Code

## Theory
A default constructor is a constructor that takes no parameters or has all default arguments. If no constructor is defined, C++ automatically provides a default constructor.

## Output
![image](https://github.com/user-attachments/assets/26466de9-3aef-4d52-bbf7-852f62b68efe)

## Conclusion
We learned how to implement default constructors in C++.

## Program 3
## Aim
To implement Parameterized constructos.

## Software used
Visual Studio Code

## Theory
A parameterized constructor lets you pass arguments when creating an object. It initializes the object's attributes with the specific values you provide. This makes it flexible, allowing for different setups based on the parameters given.

## Output
![image](https://github.com/user-attachments/assets/7337675d-9497-415b-aeb7-c35f4dda5c79)

## Conclusion
We learned how to implement parameterized constructors in C++.

## Program 4
## Aim
To implement Copy Constructors

## Software used
Visual Studio Code

## Theory
A copy constructor creates a new object as a copy of an existing object. It takes a reference to an object of the same class as its parameter and duplicates the attributes of the given object. The copy constructor is called when an object is passed by value, returned by value, or explicitly copied. It ensures that the new object has the same state as the copied object.

## Output
