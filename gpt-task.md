# Puppy Playtime

For your second programming assignment, you'll dive into the basics of object-oriented programming (OOP) with Java, focusing on class modeling. This experience will introduce you to key elements of a Java class, enhancing your understanding of object-oriented concepts.

## Deadline
Make sure to submit your work before the next scheduled class.

## Instructions
Refer to the [course instructions](https://gits-15.sys.kth.se/inda-23/course-instructions#assignments) for details on submission guidelines.

## Preparation

- Complete all readings and questions in Module 2: Looking Inside Classes.
- Use both the Canvas link and the direct webpage link provided in the instructions to access the learning materials.

## Learning Goals

This week, you will focus on:
- Designing Java classes.
- Creating and utilizing instance fields.
- Implementing a constructor method.
- Using getters and setters.
- Understanding the dot operator.
- Printing to the terminal.
- Working with the `main` method.
- Exploring scope and variable shadowing.

## Troubleshooting Guide
If you encounter any difficulties:
1. Check the [posted issues](https://gits-15.sys.kth.se/inda-23/help/issues) for similar questions from your peers.
2. If your problem is unique, create a [New Issue](https://gits-15.sys.kth.se/inda-23/help/issues/new) with a detailed title.
3. Seek assistance from a TA during the next scheduled lab.

### Assignment Overview

Imagine a park full of adorable puppies, each with unique traits. Your task is to model these puppies in Java, encapsulating their characteristics in a class.

#### Exercise 2.0 Begin the Puppy Adventure!

First, create a new Java file called `Puppy.java` in your `src` folder. This file will house your `Puppy` class. Define your class and proceed to model your very first puppy. Add the main method and create variables to store the puppy's details as follows:

- `String` name
- `int` energyLevel
- `int` happiness
- `int` hungerLevel
- `boolean` isAsleep

Test your code by running the application and ensure everything functions as expected.

#### Exercise 2.1 A Pack of Puppies

Now, let's create two more puppies, making a total of three puppies in our imaginary park. This manual creation process highlights the limitations of scalability and maintainability, which can be solved using the power of classes and objects.

#### Exercise 2.2 Fields and Objects

Refactor your puppy modeling to use fields and objects. Fields should represent each puppy's state and be defined outside the main method but within the class itself. Use the constructor method to instantiate your puppy objects.

#### Exercise 2.3 Getters and Setters

Implement getters and setters for each field to encapsulate your data and ensure controlled access. This exercise will make you comfortable using these important class methods.

#### Exercise 2.4 Constructor

Enhance your class by adding a constructor method, allowing you to specify all puppy attributes as arguments when creating a new `Puppy` object.

#### Exercise 2.5 Multiple Puppies!

Use the constructor to create two additional puppy objects. Notice how this approach is much more efficient than the manual method used earlier.

#### Exercise 2.6 `printInfo()` Method

Create a `printInfo()` method within your class to neatly print all the information about a puppy. This enhances code readability and maintainability.

#### Exercise 2.7 Puppy Interactions

Add a method to simulate interactions between puppies, such as playing or napping together. This method should modify the puppies' states based on the interaction.

#### Exercise 2.8 Understanding Variable Shadowing

Examine examples of variable shadowing to understand its implications in programming. Be prepared to discuss potential solutions and the use of the `this` keyword to resolve shadowing issues.

### Checklist

- Create your first puppy using variables inside the main method and print their information.
- Define fields for the Puppy class: `String name`, `int energyLevel`, and so on.
- Implement getters and setters for all fields.
- Create a constructor for the Puppy class.
- Design a `printInfo()` method to display a puppy's details.
- Add a method to model puppy interactions.
- Examine and understand variable shadowing examples.

### Reporting Bugs

Should you find any inconsistencies or errors in the assignment, please open a new issue with the title "Task X Error: summary of error" for acknowledgment and potential rewards.
