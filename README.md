# umat_management_system

## Overview
This project demonstrates the use of inheritance in Python by implementing a simple UMaT Management System.

## Task
The system models different types of people on campus:

- Person (Parent Class)
  - Attributes:
    - name
    - age
  - Method:
    - display_info()

- Student (Child Class)
  - Inherits from Person
  - Adds:
    - student_id
    - enroll_course()
  - Overrides display_info() while calling the parent method using super().

- Lecturer (Child Class)
  - Inherits from Person
  - Adds:
    - employee_id
    - teach_course()

## Features
- Demonstrates inheritance.
- Uses `super()` to initialize inherited attributes.
- Demonstrates method overriding.
- Demonstrates inherited and unique methods.

## Author
Frank Annan
