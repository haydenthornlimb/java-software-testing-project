# Java Software Testing Project

A Java software engineering project focused on automated unit testing, input validation, object-oriented design, and verification of application model behavior.

This project was completed as part of my Software Engineering coursework at Arizona State University. My work included developing and testing application functionality using Java and JUnit, with an emphasis on verifying expected behavior, handling invalid inputs, and testing edge cases.

> **Note:** Source code is not publicly included in this repository in order to preserve academic integrity for current and future students.

---

## Project Demo

A screencast demonstrating the project, development environment, and testing workflow is available below.

[▶ View Project Screencast on Google Drive](https://drive.google.com/drive/folders/11-_sRzTjvkuytVrA_WBf5stmNa8yhWwC?usp=drive_link)

---

## Overview

The project involved developing and testing components of a Java application using object-oriented programming principles.

A major focus of my work was creating automated unit tests to verify the behavior of application model classes. Tests were designed to cover both expected functionality and invalid or edge-case inputs.

The testing process included verifying object creation, data modification, input validation, relationships between application objects, and consistency of stored data.

---

## Testing Approach

I developed JUnit tests covering positive, negative, and edge-case scenarios.

### Object Creation

Tests verified that objects were initialized correctly with expected values, including:

- Titles
- Descriptions
- Tags
- Author information
- Automatically generated identifiers

Tests also verified that required fields were validated during object creation.

### Input Validation

Negative test cases were used to verify that invalid data was rejected appropriately.

Examples included:

- Empty titles
- Empty descriptions
- Invalid updates to required fields

Expected exceptions were verified using automated assertions.

### Object Updates

Tests verified that application objects could be modified correctly after creation.

This included updating:

- Titles
- Descriptions
- Collections of tags

Assertions were used to confirm that the object's state matched the expected values after each operation.

### Tag Handling

Testing was performed on tag-related functionality, including:

- Adding individual tags
- Updating collections of tags
- Handling empty tag collections
- Normalizing tag capitalization

For example, tags supplied with different capitalization were verified to be stored consistently in lowercase form.

### Object Relationships

Tests verified interactions between related application objects.

This included adding an answer to a question and confirming that:

- The answer was associated with the correct question
- The answer appeared in the question's collection of answers
- Stored answer data matched the expected values

### Unique Identifiers

Tests verified that independently created question objects received unique identifiers.

This helped confirm that application objects could be distinguished reliably from one another.

### Resolution State

Testing also verified functionality related to resolving questions, including confirming that information about the user responsible for resolving a question was stored correctly.

### Edge Cases

Additional tests were created for edge cases such as creating a question without any tags.

These tests helped verify that optional data could be handled without interfering with normal application behavior.

---

## Testing Strategy

The test suite was designed around three general categories:

### Positive Testing

Verified that valid inputs produced the expected results.

Examples included:

- Creating valid objects
- Updating object properties
- Adding answers
- Adding tags
- Resolving questions

### Negative Testing

Verified that invalid inputs were rejected appropriately.

Examples included:

- Empty required fields
- Invalid property updates

### Edge-Case Testing

Verified behavior under less common but valid conditions.

Examples included:

- Empty tag collections
- Mixed-case tag input
- Creation of multiple objects requiring unique identifiers

---

## Technologies & Concepts

- Java
- JUnit
- Object-Oriented Programming
- Unit Testing
- Automated Testing
- Test Case Design
- Input Validation
- Exception Handling
- Java Collections
- Javadoc
- Eclipse IDE
- Software Engineering

---

## What I Learned

This project provided hands-on experience designing automated tests for a larger Java application and strengthened my understanding of:

- Writing structured JUnit test suites
- Designing positive and negative test cases
- Identifying useful edge cases
- Using assertions to verify application behavior
- Testing exception handling and input validation
- Testing interactions between related objects
- Working with Java collections
- Applying object-oriented programming principles
- Documenting Java software with Javadoc
- Using automated testing as part of the software development process

The project also reinforced the importance of testing software behavior beyond the expected use case by considering invalid inputs, boundary conditions, and unexpected application states.

---

## Academic Project Notice

This repository documents work completed as part of Arizona State University coursework.

Source code and assignment materials are intentionally not publicly included in order to preserve course academic integrity. The repository is intended to document the project's technical concepts, testing methodology, and skills demonstrated rather than provide solutions to the original coursework.
