# Introduction
denero@berkeley.edu

## Office Hours in 781 Soda
10:30 - 11:30 Wednesday starting next week
10:00 - 11:00 Thursday starting this week
11:00 - 12:00 Thursday online (denero.org)
2:20 - 5:00 Monday 8/27 next week only

By appointment: denero.org/meet.html

Fastest way to get answers: piazza.com/berkeley/fall2018/cs61a
Contact John, Alex, & Nancy: cs61a@berkeley.edu

## Parts of the Course
lecture: Videos posted to cs61a.org before each live lecture
Lab section: the most important part of this course (next week)
Discussion section: the most important part of this course (this week)
Staff office hours: the most important part of this course (next week)
Online textbook: http://composingprograms.com

Weekly homework assignments, three exams, & four programming projects
Lots of optional special events to help you complete all this work.

## An Introduction to Computer Science
### What is Computer Science?
The study of:
  - What problems can be solved using computation
  - How to solve these problems
  - What techniques lead to effective solutions
Subfields:
  - Systems
  - Artificial Intelligence
  - Graphics
  - Security
  - Networking
  - Programming Languages
  - Theory
  - Scientific Computing

### What is This Course About?
A course about managing complexity
Mastering abstraction
Programming paradigms
An introduction to programming
Full understanding of Python fundamentals
Combining multiple ideas in large projects
How computers interpret programming languages

Different types of languages: Scheme & SQL


# Expressions
## Types of Expressions
Expression - an expression describes a computation and evaluates to a value

All expressions can use function call notation
i.e. mul(4, 5) = 4 * 5

add ( 2, 3 )
operator - operand - operand
operators and operands are also expressions, so they evaluate to values

Evaluation procedure for call expressions:
1. Evaluate the operator and then the operand subexpressions
2. Apply the function that is the value of the operator to the arguments that are the values of the operands

Expression tree - tree of expanded operand solves

mul(add(4, mul(4,6)), add(3, 5))
operand subexpression - add(4, mul(4, 6))