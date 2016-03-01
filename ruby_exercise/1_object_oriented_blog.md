# Object oriented Blog

###**Concepts used in this exercise**
  * Classes
  * Instance Methods and Instance Variables
  * String concatenation / Manipulation
  * Array operations(adding, iterating)

####**Time commitment: Low**

---

## Iteration 1 

Let’s create a Blog class where you can add Post objects. Each post will have a title, a date and a text. Create a front_page method in the Blog class that returns the front page of the blog with all of the posts in the following format: 

```
Post title 1
**************
Post 1 text
----------------
Post title 2
**************
Post 2 text
----------------
Post title 3
**************
Post 3 text
----------------
```

The posts should be ordered by date, starting with the newest.

**Steps: **
---
Think of what a blog and a post are in object / relational terms. What is a blog and a post? What attributes does each of them have? What relation do a blog and a post have? **Hint:** the blog without posts is just an empty container with the ability to add posts...Where have we seen this before?

## Iteration 2 

Lets add sponsored posts. If the post with title 2 happened to be sponsored, this is what the output should look like: 

```
Post title 1
***** *********
Post 1 text
----------------
******Sponsored Post title 2******
**************
Sponsored Post 2 text
----------------
Post title 3
**************
Post 3 text
----------------
```
**Hint:** Think of the sponsored post in Object Oriented terms. A sponsored post is going to have mostly the same attributes as our post class, but with some additional changes. We should probably extend the post class somehow…



