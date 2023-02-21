# Lox Parser

## DUE: February 28 by 2:30pm

## Table of Contents

- [Introduction](#introduction)

- [Learning](#learning)

- [Requirements](#requirements)

- [Assignment Assessment](#assignment-assessment)

- [Assistance](#assistance)

## Introduction

This assignment requires students to create an enhanced parser for the lox programming language by following Chapter 5 and Chapter 6 of the "Crafting Interpreters" textbook. You are to work in the lox team you have already set up for this lab. In addition to getting a working parser as it is implemented in the book, you are responsible for adding a small extension for the parser and provide a complete documentation for the  parser in the README of the `lox_interpreter` repository. Furthermore, each team is invited to engage in a code walkthrough and a demonstration with a TL and/or instructor during the next week's lab.

You are responsible for storing all implementation for this lab in your team's `lox_interpreter` repository. 

## Learning

To enhance your understanding of the concepts and code of this laboratory assignment, you should carefully read [Chapter 5](https://craftinginterpreters.com/representing-code.html) and [Chapter 6]() in Crafting Interpreters.

## Requirements

1. Complete working version of the parser from the textbook with addition of proper comments.
2. Small enhancement to the parser.
3. Complete documentation.
4. Participation in the walkthrough and demo.

### Working and Properly Commented Parser

- Follow [Chapter 5 in Crafting Interpreters](https://craftinginterpreters.com/representing-code.html) textbook to produce `GenerateAst.java` inside a new directory outside of `lox/` directory.
- Compile and run `GenerateAst.java` as `java GenerateAst ../lox/`, assuming this file is located in a directory one level out of `lox/`. Note, you will need to make some adjustments to the code from the book to remove references to writing "package" references in order to get it to work correctly.
- Now you should have `Expr.java` generated inside your `lox/` directory.
- Proceed with Chapter 5 to create `AstPrinter.java`. 
- Compile and run `AstPrinter.java` to see an output similar to: 

`(* (- 123) (group 45.67))`

- Now, following [Chapter 6](https://craftinginterpreters.com/parsing-expressions.html), create `Parser.java` and modify `Lox.java`.
- Compile and run `Lox.java` to see a functioning parser that is able to parse both correct and incorrect input. For example, you should verify that it handles precedence and associativity correctly.

Please, also ensure all new Java classes have standard Javadoc comments before each class and each method, and single line comments to explain lines of code

### Enhancements

Add one small enhancement (make changes or additions to the code) to make the parser better. Most enhancements might be cosmetic or add to the usability of the parser (for example, better error reporting).

### Documentation

For this part of the assignment, you are to complete the section in the README under the "Parsing" heading. In this section, you must, at the minimum, include the following:

- Visual representation of the general flow of the parsing process (for example, a flow diagram).
- Overview of the Lox grammar.
- Short summary of `Parser` class's high-level description and the functionality of its major methods, similar to information on the documentation API. This should be organized into subsections as relevant.

### Walkthrough and Demo

During our next lab, each team will demonstrate their working parser and participate in a code walkthrough. Code walkthrough is an informal analysis process with a goal of identifying defects within the code. In this case, code walkthrough will also be used to assess the understanding of the code by the team members. 

- Before next lab, each team should find time to engage in a peer code walkthrough process, where each person assigned to a specific part of the code explains the given code line by line. The goal of this exercise is to ensure everyone is comfortable with the understanding of every line of code of the parser.
- Then, during the next lab session on February 28th, each team will lead the review process for a TL/instructor who will ask questions. Teams can assign specific members to lead the review of the certain portion of the code, however questions can be directed to anyone on the team. 

## Assignment Assessment

GitHub Actions is not used in this assignment. The grade that a student receives on this assignment will have the following components. All components of the grade will be assessed manually by the instructor and the technical leaders.

- **Mastery of Verbal Explanation [up to 35%]:** Students will receive a portion of their grade when their explanations presented during the walkthrough reveal a thorough understanding of the code. Every member of the team is expected to understand every line of code being presented. The reviewer reserves to question any member of the team to assess their understanding.

- **Mastery of Technical Writing [up to 25%]:** Students will also receive a portion of their grade when the documentation reveals a proficiency of both writing skills and technical knowledge. 

- **Mastery of Technical Knowledge and Skills [up to 40%]:** Students will receive a portion of their assignment grade when their lab solution reveals that they have mastered all of the technical knowledge and skills developed during the completion of this assignment. As a part of this grade, the instructor will assess aspects of the project including, but not limited to, the completeness and correctness of the parser, the required extension, and contributions of each student to the project on GitHub.

All grades for this project will be reported through a student's gradebook GitHub repository.

## Assistance

If you are having trouble completing any part of this project, then please talk with the course instructor or technical leaders during the laboratory session. Alternatively, you may ask questions in the Discord channel for this course. Finally, you can schedule a meeting during the course instructor's office hours.
