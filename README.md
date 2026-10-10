# Unit 1 Discussion: Python OOP, Namespaces, and Copying

## Overview

This assignment explores object-oriented programming (OOP) concepts in Python, including inheritance, namespaces, and object copying.

## Learning Objectives

- Create parent and child classes
- Use inheritance to extend functionality
- Understand class and instance namespaces
- Demonstrate shallow and deep copying
- Apply object-oriented design principles

## Requirements

Complete all TODO sections in the source code:

1. Create a parent class.
2. Create a child class using inheritance.
3. Demonstrate class and instance namespaces.
4. Demonstrate shallow and deep copying.
5. Create and test objects in `main()`.
6. Add a student-created extension.

## Discussion Board Reflection

After completing the programming assignment, add this reflection to your initial discussion post in LEO.

Your reflection should be approximately 150–200 words and address the following questions:

1. What concepts or skills did you learn while completing this assignment?
2. What challenges did you encounter, and how did you overcome them?
3. Compare OOP to procedural programming.
4. Discuss the benefits of maintainability and reusability and apply this managing overhead, practical application development, and future use.

## Implementation Documentaion

- ParentClass stored a person's name and age.
- ChildClass inherited those attributes and added a student ID and courses.
- The namespace demonstration displayed class and object attributes.
- The copying demonstration showed shared versus independent nested lists. 
- Your drop_course() extension removed an enrolled course and handled missing courses.

## Reflection 

This assignment helped me connect the OOP concepts I had been reading about to a program I could run. I built a person class and extended it into a student class with an ID and courses. Using super() showed me how I could reuse the parent’s initialization, while overriding display_info() let me display the student’s additional information.

The hardest part for me was getting the code organized correctly and running it in VS Code. I had to fix indentation and separate statements that I had accidentally joined together. Seeing the results in the terminal helped me understand what my code actually did. The copying example was especially useful because adding History changed both the original and shallow copy, but left the deep copy unchanged. Adding drop_course() also gave me practice handling a course that was not enrolled.

Compared with procedural programming, OOP kept each student’s information and actions together. This made changes easier to maintain, and inheritance reduced repeated code. However, classes added setup, and deep copies used extra memory and processing. I would use simpler functions for small tasks and consider OOP for larger projects, such as a registration system that needed more student features over time.
