Unit 2 (Java) - Lesson 5 Learning Objectives
============================================

Goals
-----

- Write unit tests to verify the behavior of methods
- Identify proper behaviors for which a test should be written
- Understand the importance of testing in creating well-functioning code
- Use test-driven development to define the behavior of code before writing it, and to ensure that code is properly tested
- Use JUnit to create test

Objectives
----------

Unit Testing in Java
^^^^^^^^^^^^^^^^^^^^

- Review the fundamentals of unit testing and TDD from previous learning
- Explain and use the AAA pattern for creating tests: Arrange, Act, Assert
- Explain the importance of tests when refactoring code
- Use tests to make code self-documenting
- Explain why comments are not the best form of documenting code behavior
- Explain and use best practices for writing unit tests:
  
  - Tests should be deterministic. For example, a test should not include randomly-generated data. Also, a test should not pass part of the time and fail part of the time with the same code.
  - Tests should be grouped by related class and function
  - Tests should pass before you commit your code
  - Don't test trivial pieces of code. For example, unless getters and setters contain additional behavior, they should not be tested.

JUnit
^^^^^

- Place tests in the correct location within a Java project
- Add JUnit 4 to the project classpath
- Group related tests together within the same class
- Use the ``@Test`` annotation to mark a test method
- Use ``@Before`` to generate test data to be used by each test within a class
- Understand the behavior of ``@After``
- Run JUnit tests as a group, or individually, within IntelliJ
- Use common assertion methods: ``assertEquals``, ``assertFalse``, ``assertTrue``, ``assertNotNull``
