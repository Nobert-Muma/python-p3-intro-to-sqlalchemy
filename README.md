# Intro to SQLAlchemy

## Learning Goals

- Use an external library to simplify tasks from ORM and Advanced ORM.
- Manage database tables and schemas without ever writing SQL through Alembic.
- Use SQLAlchemy to create, read, update and delete records in a SQL database.

***

## Key Vocab

- **Migration**: the process of moving data from one or more databases to one
  or more target databases.

***

## Introduction

In our previous module, we learned about **ORMs**. Using `sqlite3` and concepts
in object-oriented programming in Python, we built tools to map Python classes
to database tables and vice-versa. This is a useful skill for your future work,
but it has some distinct limitations:

- It only works with one type of SQL database, `sqlite3`.
- It only covers the functionality that we needed for our `Dog` and `Song`
  classes.
- We won't know how other groups' ORMs work.
- Others won't know how our ORM works.

In order to address these concerns, several groups of programmers began
development on ORMs that had a broad range of compatibilites and functionality,
robust documentation, and regular maintenance to keep up with evolving
programming languages. In our curriculum, we will be working with SQLAlchemy,
a popular Python ORM.

SQLAlchemy is a great tool because it covers 

***

## Resources

- [Resource 1](https://www.python.org/doc/essays/blurb/)
- [Reused Resource][reused resource]

[reused resource]: https://docs.python.org/3/
