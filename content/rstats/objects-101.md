Title: Object Basics
Slug: objects-101
Summary: Object Basics
Date: 2016-05-01 12:00
Category: R Stats
Tags: Basics
Authors: Chris Albon



R treats almost everything in the software as an object. Objects can be individual numbers to variable names to strings of plain text. Working in R meaning manipulating these objects to make them how you want them.

In R, a collection of one or more values is called a vector. Think of vectors as a collection of numbers.


```R
# We can create a vector by creating a variable
my.age <- 29 # create an vector variable called my.age that contains the value "29"
my.age # view the contents of our.ages
```




    [1] 29




```R
our.ages <- c(29, 29, 43, 4) # create a vector variable called our.ages containing the values 29, 29, 43, and 4
our.ages # view the contents of our.ages
```




    [1] 29 29 43  4
