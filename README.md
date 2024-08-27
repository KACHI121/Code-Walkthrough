# 2300063 WALLACE KACHINGWE
# Code-Walkthrough
how to run code
# Student Management System

## Overview
This project implements a simple student management system using Python. The system allows users to add, delete, update, and view students. The code follows SOLID principles, eliminates redundancy, and adheres to the DRY, KISS, and YAGNI principles.

## How to Run
1. Clone the repository.
2. Run the `student_management.py` file in your Python environment.
3. Follow the on-screen menu to interact with the system.

## Changes Made
- Refactored the original code to follow SOLID principles.
- Introduced an abstraction layer (`IStudentRepository`) to decouple the system from the database implementation.
- Simplified the update process by making the `update_student_info` method more straightforward.
- Added a simple text-based menu for user interaction.


- **Menu Options**:
  - `1. Add Student`: Allows you to add a new student to the system.
  - `2. Update Student`: Update existing student details.
  - `3. Delete Student`: Remove a student from the system.
  - `4. View All Students`: Display all students currently in the system.

## Design Decisions
- **Single Responsibility Principle**: Each class in the system has a single responsibility, making the code easier to maintain and extend.
- **DRY Principle**: Redundant code was eliminated by abstracting common functionalities.
- **KISS Principle**: The design was simplified to make the system easier to understand and use.

## Changelog
-  Refactored code to improve adherence to SOLID principles and added a menu system.
-  Initial version with basic CRUD operations for managing students.


