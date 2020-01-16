Unit 2 (Java) - Lesson 17 Learning Objectives
=============================================

Goals
-----

- Build persistent model classes that have one-to-many and many-to-many relationships
- Understand how to model relationships in a relational database

Objectives
----------

One-to-Many Relationships
^^^^^^^^^^^^^^^^^^^^^^^^^

- Describe the one-to-many relationship as it relates to objects
- Use the following annotations and describe what they accomplish:

   - ``@OneToMany``
   - ``@JoinColumn``
   - ``@ManyToOne``

Many-to-Many Relationships
^^^^^^^^^^^^^^^^^^^^^^^^^^

- Describe many-to-many relationships
- Explain what a join table is and how it is used
- Explain what a composite key is 
- Build model classes that enable persistent many-to-many relationships
- Use the ``@ManyToMany`` annotation 
- Work with many-to-many relationships in the view and controller
- Use ``@Transactional`` to ensure data integrity in the event of an exception
