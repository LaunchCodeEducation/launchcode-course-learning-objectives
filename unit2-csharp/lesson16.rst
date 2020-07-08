Unit 2 (C#) - Lesson 16 Learning Objectives
=============================================

Goals
-----

- Understand how object-relational mapping allows object-oriented web applications to store data in relational databases
- Implement ORM for individual, non-related entities in Spring Boot

Objectives
----------

- Explain what object-relational mapping means
- Describe what a data layer is, and how it is used in ORM
- Extend ``DbContext`` to create a data layer
- Configure an ASP.NET app to connect to a MySQL database using ``appsettings.json`` and the ``ConfigureServices`` method of ``Startup.cs``
- Properly configure the ``Id`` field of a model class to function as a primary key field
- Use common ``DbSet`` methods: ``Add``, ``Remove``, ``ToList``, and ``Find``
- Use the ``SaveChanges`` method of  ``DbContext``, and understand why it is important
- Create and run migrations using the EF Core CLI tools