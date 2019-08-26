# Introduction to Object-Relational Mapping

As a relative newcomer to the programming world, terms like
_Object-Relational-Mapper_ can sound really intimidating. The nice part about
ORMs, is that they can make it easier to write code once you understand them.

You’ve already written your fair share of SQL queries in the previous section.
They usually look something like this:

```sql
SELECT * FROM schools WHERE name = 'Flatiron';
```

Object-relational-mapping allows you to write queries like the one above, as
well as much more complicated ones, using the object-oriented paradigm of your
preferred programming language--in this case that would be Ruby.

In these lessons, we'll be covering these topics:

* The benefits of ORM 
* How ORMs can abstract database logic
* Writing code that inserts data into the database
* Writing methods that can update an existing database record when changes are
  made its related Ruby object
* Identifying whether a Ruby object has already been persisted to the database
* Building a method that can either find and update or create a database record
* Scraping and saving data into a database
* How to use data to make Ruby objects
* Turning database rows into Ruby objects
* Mapping a database table to a Ruby object
* Searching a database with Ruby objects

In this section, you'll get to write in the language you are already learning
anyway. SQL is a powerful language, but most of us don’t write in it often.
Being able to leverage the fluency of Ruby to perform these actions is awesome!
