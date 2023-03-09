Unit 2 (Java) - Lesson 18 Learning Objectives
=============================================

Goals
-----

- Build persistent model classes that have one-to-one and many-to-many relationships
- Understand how these relationships are represented in a relational database

Objectives
----------

One-to-One Relationships
^^^^^^^^^^^^^^^^^^^^^^^^

- Describe one-to-one relationships
- Use ``@OneToOne`` on the owning class to establish such a relationship
- Use ``cascade = CascadeType.ALL`` to ensure child objects are saved when saving the parent object

Many-to-Many Relationships
^^^^^^^^^^^^^^^^^^^^^^^^^^

- Describe many-to-many relationships
- Explain what a join table is and how it is used
- Explain what a composite key is 
- Build model classes that enable persistent many-to-many relationships
- Use the ``@ManyToMany`` annotation with ``mappedBy`` to establish bi-directional many-to-many relationships
- Use data transfer objects (DTOs) to establish relationships between many-to-many entities in a controller
