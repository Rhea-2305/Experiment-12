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
![image](https://github.com/user-attachments/assets/ee4119a2-c1e4-4ecd-949f-b05e7ab76fd3)

## Conclusion
We learned how to implement copy constructors in C++.

## Program 5
## Aim
To use Constructors with default Arguments.

## Software used
Visual Studio Code

## Theory
These constructors allow one or more parameters to have default values. When an object is created, if no argument is provided for these parameters, the default values are used. This feature combines the flexibility of parameterized constructors with default behavior.

## Output
![image](https://github.com/user-attachments/assets/758cc0da-3bbd-4561-b7a8-87117d706a3f)

## Conclusion
We learned how to use constructors with default arguments in C++.

## Program 6
## Aim
To implement destructors.

## Software used
Visual Studio Code

## Theory
A destructor is a special member function that is automatically called when an object goes out of scope or is explicitly deleted. The destructor has the same name as the class, preceded by a tilde (~), and it has no return type or parameters. Destructors are primarily used to release resources, such as memory or file handles, ensuring that objects clean up after themselves when they are no longer needed.

## Output
![image](https://github.com/user-attachments/assets/3dcf3d14-09ed-4b08-957f-c71eb1bf37aa)

## Conclusion
We learned how to implement destructors in C++.
