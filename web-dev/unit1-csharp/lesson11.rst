Unit 1 (C#) - Lesson 11 Learning Objectives
===========================================

Goals
-----

- Write unit tests to verify the behavior of methods
- Identify proper behaviors for which a test should be written
- Understand the importance of testing in creating well-functioning code
- Use test-driven development to define the behavior of code before writing it, 
  and to ensure that code is properly tested
- Use MSTest to create unit tests

Objectives
----------

Unit Testing in C#
^^^^^^^^^^^^^^^^^^

- Describe the importance of unit testing
- Explain what a unit test is
- Describe how the concept of assertions allows us to define expected behavior of code
- Identify test cases, including test case types: positive, negative, edge

- Explain and use the AAA pattern for creating tests: Arrange, Act, Assert
- Explain the importance of tests when refactoring code
- Use tests to make code self-documenting
- Explain why comments are not the best form of documenting code behavior
- Explain and use best practices for writing unit tests:
  
  - Tests should be deterministic: they should not include randomly-generated data,
    nor should it pass part of the time and fail at other times 
  - Tests should be grouped by related class and function
  - Tests should pass before your code is committed
  - Tests should not be trivial - ie, unless getters and setters contain 
    specialized behavior, they should not be tested

MSTest
^^^^^^

- Place tests in the correct location within a C# project
- Add MSTest to the solution
- Group related tests together within the same class
- Use the ``[TestClass]`` and ``[TestMethod]`` attributes to mark a test classes and methods
- Run tests as a group, or individually, within Visual Studio
- Use common ``Assert`` methods: ``AreEqual()``, ``IsFalse()``, ``IsTrue()``, ``IsNotNull()``
