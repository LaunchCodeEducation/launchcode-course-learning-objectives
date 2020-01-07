Unit 2 (Java) - Lesson 16 Learning Objectives
=============================================

Goals
-----

- Understand how object-relational mapping allows object-oriented web applications to store data in relational databases
- Implement ORM with one-to-one and one-to-many relationships in Spring Boot

Objectives
----------

- Explain what object-relational mapping refers to
- Describe what a data layer is and how it is used in ORM
- Describe the one-to-many relationship
- Use the following annotations and describe what they accomplish:
   - ``@Entity``
   - ``@Id``
   - ``@GeneratedValue``
   - ``@Autowired``
   - ``@Repository``
   - ``@Transactional`` 
   - ``@OneToMany``
   - ``@JoinColumn``
   - ``@ManyToOne``
- Explain why entity classes need no-arg constructors 
- Create repository interfaces extending ``CrudRepository``
- Explain how repositories enable data access
- Use common ``CrudRepository`` methods: ``delete``, ``deleteById``, ``findAll``, ``findById``, ``save``
- Understand how Spring Data, JPA, and Hibernate work together to fully implement ORM in Spring Boot 
