Unit 2 (Java) - Lesson 12 Learning Objectives
=============================================

Goals
-----

- Validate form submission data using annotations and model binding
- Use enum types to represent categories of related objects

Objectives
----------

- Use Java Validation API annotations (from ``javax.validation.constraints``) on model classes, including ``@Min``, ``@Max``, ``@Size``, ``@Email``, ``@NotBlank``, and ``@NotNull``
- Use ``@Valid`` on model objects in a controller to check for validation errors
- Explain how and when Spring validates model objects that are bound during a request
- Display error messages in the view
- Use the Thymeleaf ``th:object`` tag to bind an object to a form
- Use ``th:field`` to auto-generate field settings
- Use ``th:errors`` to display field-specific error messages 
- Explain the difference between ``*{}`` and ``${}`` in Thymeleaf
- Explain what enum types are and when they should be used
- Create enums with custom properties
- Represent enum data in a view using a ``<select>`` element
