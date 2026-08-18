# Java Software Engineering Projects

A collection of Java software engineering work completed as part of my coursework at Arizona State University, demonstrating application development, object-oriented programming, GUI development, data management, automated testing, input validation, and technical documentation.

This repository serves as a portfolio overview of the technical concepts and development practices I applied throughout the course.

> **Note:** Source code and original assignment materials are intentionally not publicly included in order to preserve academic integrity. Project demonstrations and descriptions are provided instead.

---

## Project Overview

Throughout the course, I worked on components of a Java application that incorporated user interfaces, application models, data management, validation, testing, and documentation.

My work provided experience with several stages of the software development process, including:

- Designing and working with Java application components
- Developing and interacting with graphical user interfaces
- Working with application data and model objects
- Implementing and testing question-and-answer functionality
- Validating user input and application state
- Designing automated unit tests
- Testing positive, negative, and edge-case scenarios
- Working with relationships between application objects
- Generating and reviewing Javadoc documentation
- Using Eclipse as a Java development environment

---

# Application Development

One portion of my coursework involved working with a Java application containing graphical interfaces and functionality for managing application data.

The application included question-and-answer functionality and interfaces for interacting with stored information.

This work provided hands-on experience working with multiple components of a larger Java application rather than isolated programming exercises.

## Concepts Demonstrated

- Java application development
- Object-oriented programming
- Graphical user interfaces
- Application models
- Data management
- User input handling
- Question-and-answer functionality
- Application navigation
- Integration between application components

---

## Application Demonstration

The following screencast demonstrates the Java application and its functionality.

### Java Application – GUI, Data Management & Question/Answer Functionality

The demonstration showcases the running application and interaction with its graphical interface and question-and-answer functionality.

[▶ View Application Demonstration on Google Drive](https://drive.google.com/drive/folders/11-_sRzTjvkuytVrA_WBf5stmNa8yhWwC?usp=drive_link)

---

# Automated Software Testing

Another major component of my coursework involved developing automated tests for Java application models.

I created JUnit tests designed to verify both normal application behavior and the application's response to invalid or unusual inputs.

Testing covered object creation, updates, validation, object relationships, data normalization, identifiers, and edge cases.

---

## Unit Testing

The test suite included positive, negative, and edge-case testing.

### Object Creation

Tests verified that application objects were initialized correctly with expected information such as:

- Titles
- Descriptions
- Tags
- Author information
- Generated identifiers

Tests also verified that required information was validated during object creation.

### Input Validation

Negative tests verified that invalid data was rejected appropriately.

Examples included testing:

- Empty required titles
- Empty required descriptions
- Invalid updates to required fields
- Expected exception behavior

These tests helped verify that invalid application states could not be introduced through normal object operations.

### Object Updates

Tests verified that existing application objects could be modified successfully.

Test cases covered updates to:

- Titles
- Descriptions
- Collections of tags

Assertions were used to verify that the resulting object state matched the expected values.

### Tag Processing

Testing also covered application behavior involving tags, including:

- Adding individual tags
- Updating tag collections
- Handling empty tag collections
- Normalizing capitalization

For example, mixed-case tag input was tested to verify that tags were stored consistently in lowercase.

### Question and Answer Relationships

Tests verified interactions between question and answer objects.

This included adding an answer to a question and confirming that:

- The answer was successfully associated with the question
- The question's answer collection was updated
- Stored answer information matched the expected data

### Unique Identifiers

Tests verified that independently created question objects received unique identifiers.

This helped ensure that separate application objects could be reliably distinguished from one another.

### Question Resolution

Testing also covered question-resolution functionality, including verification that information identifying the user responsible for resolving a question was stored correctly.

### Edge Cases

Additional tests covered valid but less common application states, such as creating a question without any tags.

Testing these cases helped ensure that optional information could be handled without interfering with expected application behavior.

---

# Testing Strategy

I structured testing around three primary categories.

## Positive Testing

Verified that valid inputs and operations produced the expected results.

Examples included:

- Creating valid objects
- Updating properties
- Adding answers
- Adding tags
- Resolving questions

## Negative Testing

Verified that invalid inputs were rejected appropriately.

Examples included:

- Missing required information
- Empty required fields
- Invalid property updates

Expected exceptions were checked using automated assertions.

## Edge-Case Testing

Verified application behavior under less common conditions.

Examples included:

- Empty tag collections
- Mixed-case tag input
- Multiple objects requiring unique identifiers

---

## Testing & Documentation Demonstration

The following screencast demonstrates the testing and documentation workflow used during the project.

### Java Application – Unit Testing & Javadoc Documentation

The demonstration showcases automated testing and project documentation within the Java development environment.

[▶ View Testing & Documentation Demonstration on Google Drive](https://drive.google.com/drive/folders/11-_sRzTjvkuytVrA_WBf5stmNa8yhWwC?usp=drive_link)

---

# Development & Testing Workflow

The coursework provided experience working through several parts of a typical software development workflow:

```text
Application Requirements
        |
        v
Java Application Components
        |
        v
Application Models & Data
        |
        v
GUI / User Interaction
        |
        v
Input Validation
        |
        v
JUnit Test Development
        |
        v
Positive / Negative / Edge-Case Testing
        |
        v
Documentation & Verification
```

This helped connect implementation with testing rather than treating software testing as a separate activity.

---

# Technologies & Concepts

- Java
- JUnit
- Eclipse IDE
- Javadoc
- Object-Oriented Programming
- Graphical User Interfaces
- Unit Testing
- Automated Testing
- Test Case Design
- Input Validation
- Exception Handling
- Java Collections
- Application Models
- Software Documentation
- Software Engineering

---

# What I Learned

This coursework strengthened my understanding of how different parts of software development fit together within a larger Java application.

In particular, I gained hands-on experience with:

- Developing and working with multi-component Java applications
- Applying object-oriented programming principles
- Working with graphical application interfaces
- Managing interactions between application objects
- Designing structured JUnit test suites
- Writing positive and negative test cases
- Identifying useful edge cases
- Using assertions to verify application behavior
- Testing input validation and exception handling
- Testing relationships between related objects
- Working with Java collections
- Generating and reviewing Javadoc documentation
- Using automated testing as part of the development process

One of the most valuable aspects of the coursework was learning to consider software from both the development and testing perspectives. Functionality needed not only to work under expected conditions, but also to behave predictably when given invalid or unexpected input.

---

# Project Media

Because source code cannot be publicly distributed, project screencasts are provided to demonstrate the functionality and development work described in this repository.

### Application Demonstration

**Java Application – GUI, Data Management & Question/Answer Functionality**

[▶ View on Google Drive](https://drive.google.com/drive/folders/11-_sRzTjvkuytVrA_WBf5stmNa8yhWwC?usp=drive_link)

### Testing & Documentation Demonstration

**Java Application – Unit Testing & Javadoc Documentation**

[▶ View on Google Drive](https://drive.google.com/drive/folders/11-_sRzTjvkuytVrA_WBf5stmNa8yhWwC?usp=drive_link)

---

# Academic Project Notice

This repository documents work completed as part of Arizona State University coursework.

Source code and original assignment materials are intentionally not publicly included in order to preserve academic integrity for current and future students.

The repository is intended to document the software engineering concepts, development practices, testing methodology, and technical skills demonstrated through my work rather than provide solutions to the original coursework.
