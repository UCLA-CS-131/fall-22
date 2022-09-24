---
layout: page
title: About CS 131
description: >-
    Course policies and information.
permalink: index.html
---

# About CS 131 / Syllabus
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

----

## Instructors and Class Meetings

See also: [staff]({{site.baseurl}}/staff/), [weekly schedule]({{site.baseurl}}/schedule/).

Instructor: Carey Nachenberg

Office: Engineering VI 299

Class times: M/W 2-4pm

Course Location: Northwest Auditorium

Instructor Office Hours: Eng VI room 464

Office Hours: Mon/Wed 4-5pm or by appointment


| TA | Section | Discussion | Office Hours | Email |
|:---|:--------|:-----------|:-------------|:------|
| Matthew Wang | 1A | Fri 10 AM - 11:50 AM | Mon/Wed 11 AM - 12 PM, Boelter 3256-S | [matt@matthewwang.me](mailto:matt@matthewwang.me) |
| Ashwin Ranade | 1B | Fri 12 PM - 1:50 PM | Wed 12 PM - 2 PM, Boelter 3256-S | [ashwin.ranade@cs.ucla.edu](mailto:ashwin.ranade@cs.ucla.edu) |
| Boyan Ding | 1C | Fri 2 PM - 3:50 PM | Thu 3-5 PM, Eng VI 392 | [dboyan@cs.ucla.edu](mailto:dboyan@cs.ucla.edu) |
| Siddarth Krishnamoorthy | 1D | Fri 4 PM - 5:50 PM | Tue/Thu 10 AM - 11 AM, Boelter 3256-S | [siddarthk@cs.ucla.edu](mailto:siddarthk@cs.ucla.edu) |


## Topics and Exams

See also: [course calendar]({{site.baseurl}}/calendar/).

<details markdown="0">
<summary markdown="0">Toggle Course Topics and Exams</summary>
<div markdown="1">
**Week 1: 9/26 and 9/28**

- Course Introduction
    - History, course methodology, syntax vs semantics, compilers/interpreters/linkers, Intro to functional programming
- Functional Programming, part 1
    - Haskell Intro, Haskell data types, list deep-dive, comprehensions

**Week 2: 10/3 and 10/5**

- Functional Programming, part 2
    - Haskell functions, local bindings, control flow (incl. guards), pattern matching, 1st-class and higher order functions
- Functional Programming, part 3
    - Map/filter/reduce, lambdas/closures, currying, partial application, algebraic data types, immutable data structures [FP guest interview: Simon Peyton Jones]

**Week 3: 10/10 and 10/12**

- Python, part 1
    - The Python shell, program execution, functions, types/variables, looping, classes/inheritance, objects and references, garbage collection, duck typing
- Python, part 2
    - Composite types (strings, lists, tuples, dictionaries, sets), parameter passing, exception handling, modules, functional influences

**Week 4: 10/17 and 10/19**

- Data palooza, part 1
    - Variables vs values, types, typing strategies (static vs. dynamic)
- Data palooza, part 2
    - Typing strategies, cont. (weak vs. strong), supertypes and subtypes, casting and conversion, scoping strategies (lexical vs. dynamic)

**Week 5: 10/24 and 10/26**

- Data palooza, part 3
    - Binding semantics (value, reference, object reference, name/need), memory safety (garbage collection, smart pointers, object destruction/finalization), mutability
- Function palooza, part 1
    - Parameter passing (pass-by-..., variadics, named parameters, etc)

**Week 6: 10/31 and 11/2**

- Function palooza, part 2 [FP guest interview: Bjarne Stroustrup]
    - Returning values and error handling (error objects, optionals, assertions/invariants, exceptions, panics)
- Midterm exam

**Week 7: 11/7 and 11/9**

- Function palooza, part 3
    - First-class functions (lambdas/closures across languages, capturing strategies), polymorphism (subtype, ad hoc, parametric - generics vs. templates)
- OOP palooza, part 1
    - OOP intro, OOP history, encapsulation, classes (class fields/methods, construction/destruction/finalization)

**Week 8: 11/14 and 11/16**   [OOP guest interview: Alan Kay, timing TBD]

- OOP palooza, part 2
    - Classes cont. (this and self, access modifiers, properties, accessors/mutators), inheritance approaches (interface, subclassing)
- OOP palooza, part 3
    - Inheritance approaches cont. (implementation, prototypal), inheritance topics (construction/destruction/finalization, method overriding, multiple inheritance, abstract classes/methods)

**Week 9: 11/21 and 11/23**

- OOP palooza, part 4
    - Inheritance topics cont. (inheritance and typing), subtype polymorphism, dynamic dispatch, design patterns, OOP design patterns (SOLID)
- Control palooza, part 1
    - Expression evaluation (associativity, order of evaluation), short circuiting, control statements (conditionals, iteration), iterators (objects, generators, via 1st-class functions)

**Week 10: 11/28 and 11/30**

- Control palooza, part 2
    - Concurrency (multi-threading, event loop), multithreading (fork-join), event-loop (events, chaining background operations - callbacks, promises, async/await)
- Logical programming
    - History, language overview, statements (facts, rules, goals), resolution, unification

**Finals Week**

- Final exam on Friday, December 9th, from 8am-11am
</div>
</details>

## Assignments

Assignments will take the form of homework and larger class projects. Homework will be graded on effort only. By "effort" we mean that you have attempted/solved all of the problems, provided solutions or partial solutions for each, and have documented where you got stuck on problems that you could not figure out. Class projects will be fully graded for correctness. All assignments will be due at 11:59pm on their due date. Homework and assignments that are turned in late will be penalized at the rate of 5% per hour past the deadline.

### Assignment Schedule

See also: [course calendar]({{site.baseurl}}/calendar/).

<details markdown="0">
<summary markdown="0">Toggle Assignment Schedule</summary>
<div markdown="1">
Week 1: 9/26 and 9/28

- 9/29 Homework 1 posted (basic Haskell topics, install Haskell and Python 3)

Week 2: 10/3 and 10/5

- 10/6 Homework 1 due
- 10/6 Homework 2 posted (advanced Haskell topics)

Week 3: 10/10 and 10/12

- 10/13 Homework 2 due
- 10/13 Homework 3 posted (Python topics)
- 10/13 Project 1 posted (v1 language implementation)

Week 4: 10/17 and 10/19

- 10/20 Homework 3 due
- 10/20 Homework 4 posted (typing, casting, scoping, binding strategies)

Week 5: 10/24 and 10/26

- 10/23 Project 1 due
- 10/27 Homework 4 due
- 10/27 Homework 5 posted (pass-by, error handling,lambdas/closures, polymorphism)
- 10/27 Project 2 posted (v2 language implementation)

Week 6: 10/31 and 11/2

- 11/2 Midterm
- 11/4 (fri) Homework 5 due

Week 7: 11/7 and 11/9

- 11/6 Project 2 due
- 11/11 Project 3 posted (v3 language implementation)

Week 8: 11/14 and 11/16

- 11/17 Homework 6 posted (OOP topics)

Week 9: 11/21 and 11/23

- 11/20 Project 3 due
- 11/23 Homework 6 due
- 11/23 Homework 7 posted (short circuiting, looping, iterators, concurrency, logic programming)

Week 10: 11/28 and 11/30

- 12/1 Homework 7 due
- 12/1 Homework 8 posted

Finals week:

- 12/8 Homework 8 due
</div>
</details>

## Examinations

The midterm will cover material from the first six weeks of lectures and discussion sections. The final examination will cover material from the entire course. Missing the final for any reason will result in a final exam score of zero.

## Grading

Your grade in the course will be determined from your total score, although a final exam score below 40 may subject you to a failing grade regardless of your total score. This course will be “curved” as follows:

- 90% or higher always earns an A- or higher, 80% or higher always earns a B- or higher, etc. - this is regardless of the class median
- If the class’s median point total is lower than 80%, then the thresholds for earning each grade will be normalized downward as necessary

The total score is determined from the graded materials as follows:


| Item         | % of Grade                  |
|:-------------|:----------------------------|
| Project # 1  | 10% (graded on correctness) |
| Project # 2  | 10% (graded on correctness) |
| Project # 3  | 10% (graded on correctness) |
| Homework     | 10% (graded on effort only) |
| Midterm      | 25%                         |
| Final Exam   | 35%                         |

## Textbook

There is no required textbook for this class (I couldn’t find any that I liked). The class powerpoint slides will serve as our canonical source.

## Lecture and Discussion Sections

You will be responsible for all material covered in both lecture and discussion sections. You are STRONGLY encouraged to attend discussion sections.


## Acceptable Collaboration/Academic Integrity

Homework: Since your homework is graded only based on effort, you may collaborate in any reasonable way you like that best enables you to learn the course material (simply copying solutions would not be a reasonable way to collaborate). Use the homework as means to prepare for exams and solidify your understanding.

Projects: You may discuss general approaches/ideas, but refrain from sharing source code or pseudocode. Also, it is not acceptable to debug a classmate’s code for them or identify problems in their solution.
