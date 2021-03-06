# Variables 1

---

Use with:
* CWC Prototype 1: Lesson 3: Threshold Concept: Variables
* CS Discoveries: Unit 3: Lesson ?: ?

This activity is used to introduce variables.

A _variable_ is a named "container" that holds a value that can change as the program runs. The name of the variable is the "label" on the container. Knowing the name of a variable allows us to use the value stored in the container without needing to know the actual value. As a visual, use a photo or physical example of a one dimensional array of something (mailboxes, jars on a shelf, etc.). So we could say the fourth jar from the left (the address in memory) or we could give it a (symbolic) label – a name with descriptive value that we can use instead of the address to refer to the variable. The lable is a kind of shorthand for the address.

Variables get values by assignment. In C# the _assignment operator_ is the equal sign (**=**). The _expression_ on the right hand side of the equal sign is _evaluated_ and the result is stored in the _memory location_ (container). The ability to assign values to variables implies that the value of a variable can change as a program runs. This ability is one of the most important in programming. Literal values don't have this ability.

All values in a program are numbers, patterns of bits. Even values that we see as characters or strings are represented in the program as numbers. Therefore, in C#, we need to specify the _type_ of the variable. We need to tell the compiler how to interpret the bit pattern. They need to be **declared.** The type of the variable tells the compiler how much storage to allocate and how to make sense of the bits (what they "mean").

Prior knowledge:
* Basic concepts of binary numbers.
* Everything a computer does is manipulating binary patterns (numbers).
* Keywords.

---

## Learning Objectives
I can:
1. _Declare_ a _variable_.
1. _Initialize_ a variable by _assigning_ a _value_ to it.
1. Use the value of a variable in an _expression._

* Explain and show examples of the terms _variable, value,_ and _expression_ in samples of C# code.
* "Walk" another programmer through an expression with variables. Communicate to the programmer what the expression is doing. For example "Make the camera follow the car by assigning a value of the camera's transform that is the sum of car's transform plus the cameraOffset."

Questions:
* What does a variable declaration look like?
* What does it mean to declare a variable?
* What is the _type_ of a variable?
* Why does the type of a variable matter?
* What is the _access modifier_ of a variable?
* How do you assign a value to a variable?
* How do you use the value of a variable?
* Why is it necessary to perform operations on variables of the same type (e.g., adding a Vector3 to a Vector3 and not doing something like adding an int to a Vector3).
