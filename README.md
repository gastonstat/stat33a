# STAT 33A - Introduction to Programming in R

- __Description__: This course introduces the R statistical software to students with minimal prior exposure to programming. The course aims to prepare students to carry out a basic data analysis and to write simple functions. The focus is on the computational model that underlies the R language with the goal of providing a foundation for further coding. Topics include (not necessarily covered in the following order): 

    + Data types and data structures in R (e.g. vectors, arrays, lists, data frames)
    + Tools for data manipulation
    + Tools for data visualization
    + the REPL (read-evaluate-print loop) evaluation model
    + Control flow structures (e.g. conditionals, iterations)
    + Writing simple functions
    + Function calls
    + Argument matching
    + Data input/output
    + The formula language of R (time permitting)

- __Instructor__: [Gaston Sanchez](https://www.gastonsanchez.com)

- __Lecture__: 1 hour of lecture per week

- __Lab__: 1 hour of laboratory per week

- __Assignments__: biweekly HW assignments

- __Exams__: one midterm exam, and final test

- __Texts and Notes__:
    + [Breaking the Ice with R](https://www.gastonsanchez.com/R-ice-breaker)
    + [R Coding Basics](https://www.gastonsanchez.com/R-coding-basics)
    + [Rolling Dice](https://www.gastonsanchez.com/R-rolling-dice)
    + [Handling Strings with R](https://leanpub.com/r4strings)
    + [Tidy Hurricanes](https://www.gastonsanchez.com/R-tidy-hurricanes)
    + Prof. Sanchez's slides

- __LMS__: the specific learning resources of a given semester are shared in the Learning Management Sysment (LMS) approved by Campus authorities (e.g. bCourses, Canvas)

- __Policies__:
    + [Lab](https://github.com/gastonstat/course-policies/blob/main/policy-lab.md)
    + [HW](https://github.com/gastonstat/course-policies/blob/main/policy-hw.md)
    + [Email](https://github.com/gastonstat/course-policies/blob/main/policy-email.md)
    + [Academic Integrity](https://github.com/gastonstat/course-policies/blob/main/policy-academic-integrity.md)


-----


## 1. Introduction

:card_index: __ABOUT__:

We begin with the usual review of the course policies, logistics, overall expectations, topics in a nutshell, etc. At the computational level, you'll get introduced to RStudio and R.

<br>

:book: __READING__:

- Slides
- [Breaking the Ice with R](https://www.gastonsanchez.com/R-ice-breaker)

<br>

:pencil2: __TOPICS__:

+ __Introduction__
    - About the course
    - First contact with R and RStudio


-----


## 2. Markdown

:card_index: __ABOUT__:

You'll get introduced to Markdown and its use in dynamic computational documents (e.g. `Rmd` and `qmd` files).

<br>

:book: __READING__:

- [Breaking the Ice with R](https://www.gastonsanchez.com/R-ice-breaker)

<br>

:pencil2: __TOPICS__:

+ __Markdown__
    - Markdown syntax
    - R Markdown (`Rmd`) files


-----


## 3. Data Types and Vectors

:card_index: __ABOUT__:

In this week we describe data types and their implementation as vectors (the most fundamental data object in R).

<br>

:book: __READING__:

- [R Coding Basics](https://www.gastonsanchez.com/R-coding-basics)

<br>

:pencil2: __TOPICS__:

+ __Data Types__
    - atomic types (e.g. logical, integer, double, character)
    - coercion


-----


## 4. More About Vectors

:card_index: __ABOUT__:

We continue describing more aspects about vectors, specifically: 1) the notion of vectorized code, 2) the recycling principle, and 3) the so-called subsetting also known as subindexing or subscripting.

<br>

:book: __READING__:

- [R Coding Basics](https://www.gastonsanchez.com/R-coding-basics)

<br>

:pencil2: __TOPICS__:

+ __About Vectors__
    - Vectorization
    - Recycling principle
    - Subsetting


-----


## 5. Other Atomic Objects

:card_index: __ABOUT__:

We continue describing more atomic objects such as arrays (N-dimensional objects) and matrices (2-dimensional arrays).

<br>

:book: __READING__:

- [R Coding Basics](https://www.gastonsanchez.com/R-coding-basics)

<br>

:pencil2: __TOPICS__:

+ __More atomic objects__
    - Create simple matrices with matrix()
    - Describe and give examples of matrix subsetting (subscripting, indexing)
    - Explain in what sense a matrix is a 2-dimensional object


-----


## 6. Non-atomic Objects

:card_index: __ABOUT__:

In this week, we discuss lists, which are the most generic kind of data container in R.

<br>

:book: __READING__:

- [R Coding Basics](https://www.gastonsanchez.com/R-coding-basics)

<br>

:pencil2: __TOPICS__:

+ __Lists__
    - Manipulation of lists
    - Lists as one dimensional obejcts
    - Subsetting lists


-----


## 7. Data Frames

:card_index: __ABOUT__:

In this week, we discuss the basics of data frames, which are the dedicated object in R for handling tabular data sets.

<br>

:book: __READING__:

- [R Coding Basics](https://www.gastonsanchez.com/R-coding-basics)

<br>

:pencil2: __TOPICS__:

+ __Data Frames__
    - manipulation data frames (the "classic" way)
    - data frames as lists
    - data frames as two dimensional objects


-----


## 8. Introduction to Functions

:card_index: __ABOUT__:

You don’t need to be an expert programmer to use R, but learning more about programming allows you to automate common tasks, and solve new problems with greater ease. We'll discuss how to write basic functions, and the notion of R expressions.

<br>

:book: __READING__:

- [R Coding Basics](https://www.gastonsanchez.com/R-coding-basics)

<br>

:pencil2: __TOPICS__:

+ __Functions__
    - Main parts of a function (i.e. anatomy of a function)
    - Examples for creating a function
    - Concepts of an R compound expression
 

-----


## 9. Conditional "if-else" statements

:card_index: __ABOUT__:

If-else statements are one of the fundamental programming structures available in all programming languages. Simply put, an if-else statement executes a block of code if a specified condition is true. If the condition is false, another block of code can be executed.

<br>

:book: __READING__:

- [R Coding Basics](https://www.gastonsanchez.com/R-coding-basics)

<br>

:pencil2: __TOPICS__:

+ __If-else statements__
    - Anatomy of an `if-else` statement
    - Use of an `if-else` statements when writing functions to decide what code to execute
 

-----


## 10. Iterations

:card_index: __ABOUT__:

In addition to writing functions to reduce duplication in your code, you also need to learn about iteration, which helps you when you need to do the same operation several times. Namely, we review control flow structures such as for loops, while loops, repeat loops, and the apply family functions.

<br>

:book: __READING__:

- [R Coding Basics](https://www.gastonsanchez.com/R-coding-basics)

<br>

:pencil2: __TOPICS__:

+ __Loops__
    - Write for loops to repeat the same operation a given number of times
    - Write while loops to repeat the same operation an unknown number of time

 
-----


## 11. Manipulation of strings

:card_index: __ABOUT__:

Why should you learn about character string manipulation and working with text data? Well, because a considerable amount of information and data is precisely in the form of text. And sooner or later you will have to deal with some kind of string manipulation in most programming activities. 

<br>

:book: __READING__:

- Slides

<br>

:pencil2: __TOPICS__:

+ __Basic string processing__
    - set of functions to perform basic manipulation of character strings.


-----


## 12. Regular Expressions (part 1)

:card_index: __ABOUT__:

A considerable amount of information and data is in the form of text. To unleash the power of string manipulation, you need to learn about Regular Expressions (or regex). Namely, regular expressions allow you to describe a certain amount of text called "patterns". We'll describe the basic concepts of regex and the common operations to match text patterns. 

<br>

:book: __READING__:

- Slides

<br>

:pencil2: __TOPICS__:

+ __Basic regex__
    - literal characters
    - wildcard metacharacter
    - character sets
 

-----


## 13. Regular Expressions (part 2)

:card_index: __ABOUT__:

A considerable amount of information and data is in the form of text. To unleash the power of string manipulation, you need to learn about Regular Expressions (or regex). Namely, regular expressions allow you to describe a certain amount of text called "patterns". We'll describe the basic concepts of regex and the common operations to match text patterns. 

<br>

:book: __READING__:

- Slides

<br>

:pencil2: __TOPICS__:

+ __More regex__
    - character ranges
    - posix classes
    - anchors
    - modifiers and quantifiers
 

