# Abstraction

**Process of hiding the basic implementation of an object and make end user to easily access the functionality of the same**

Achieved using Interface and Abstract

     - Ex1: Interface gives 100% abstraction. Because if one of your class wants to implement an interface, it'll get a proper structure 
            and functionality defined in interface and you can give your own implementaion for the same. So here, Interface helped
            you in shaping your Class/Entity/Object. 
            Also Abstract class gives 0-100% abstraction based on the requirement of the abstracted class.
     - Ex2: JDBCTemplate Class has abstracted the basic configuration required to make a DB connection and preparing the statment and 
            mapping the results and also handling & translating the SQLException during connection if any to Data Access exception.

# Encapsulation (a) Data Hiding
**Process of wrapping up all the properties and functionalities of an object/entity into a single module**

Achieved using Access modifiers such as private, protected, public and default

    - Ex1 : Java Beans or POJO classes are better examples since they bind their data members and provide access to the same only 
            through getters and setters in order to maintain data hiding and restricting direct access.


# Inheritance
**Helps in achieving the relationship between the similar classes by sharing the common attributes and behaviours**






# Polymorphism
**Helps in making a different functionalities for the same behaviour based on the different inputs**



