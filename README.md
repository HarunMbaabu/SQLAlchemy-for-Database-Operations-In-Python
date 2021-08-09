SQLAlchemy for Database Operations In Python


![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/v59cyq01vls0v1dq89em.png)

**SQLAlchemy** is an open-source SQL toolkit and object-relational mapper(ORM) for Python.

It facilitates communication between Python programs and databases. Most of the time, this library is used as an ORM tool.  

**SQLAlchemy** offers several benefits over the raw SQL approach, including:

**1). Cleaner code:** Having SQL code as Python strings gets messy pretty quickly,

**2). More secure code:** Using SQLAlchemy's ORM functionalities can help mitigate against vulnerabilities such as SQL injection,

**3). Simpler logic:** SQLAlchemy allows us to abstract all of our database logic into Python objects. Instead of having to think on a table, row, and column level, we can consider everything on a class, instance, and attribute level. 

SQLAlchemy is best understood by thinking of it as two distinct components, SQLAlchemy Core and SQLAlchemy ORM. 

The latter is built on top of the former, but you can use either component exclusively to build your application, depending on which level of abstraction you prefer. Let's take a quick look at some comparable insert statements, using raw SQL, the SQLAlchemy Expression Language, and the SQLAlchemy ORM. 

**READ MORE:** https://dev.to/grayhat/getting-started-with-sqlalchemy-for-database-operations-in-python-5b5p 
