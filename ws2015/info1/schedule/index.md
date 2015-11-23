---
title: Schedule
author: kleinen
layout: schedule
---



Please note that there will be no Info1 classes in the first week due to introductionary things.
 In the second week, there will also be no lectures and due to a conference -
 I found no sensible time slot to move our first lab to, so we'll be starting off in the third week.

This schedule is tentative and subject to change!



| Week | KW | Date            | Lecture                                                                                      | Lab                                         |
|:-----|:---|:----------------|:---------------------------------------------------------------------------------------------|:--------------------------------------------|
| 1    | 41 | Tue, 2015-10-13 | no class                                                                                     | [Lab Startup](../labs/exercise-00.html)     |
|      |    | Thu, 2015-10-15 | no class                                                                                     |                                             |
| 2    | 42 | Tue, 2015-10-20 | Introduction to Class & Kara Programming                                                     | [Exercise 01 a](../labs/exercise-01-a.html) |
|      |    | Thu, 2015-10-22 | Kara Programming: Instructions, Methods, Variables, Loops, Conditionals                      |                                             |
| 3    | 43 | Tue, 2015-10-27 | Kara Roundup, Kara and its World as Objects                                                  | [Exercise 01 b](../labs/exercise-01-b.html) |
|      |    | Thu, 2015-10-29 | Objects, Classes, Methods, BlueJ, Parameters,  Compiler                                      |                                             |
| 4    | 44 | Tue, 2015-11-03 | Class Definitions, Fields, Constructors, Methods, Parameters, Assignment, Getters and Setter | [Exercise 02](../labs/exercise-02.html)     |
|      |    | Thu, 2015-11-05 | Printing to the command line, Conditional, Local Variables, Expressions                      |                                             |
| 5    | 45 | Tue, 2015-11-10 | Abstraction, Modularization, Object Interaction                                              | [Exercise 03](../labs/exercise-03.html)     |
|      |    | Thu, 2015-11-12 | Object Creation, Object and Class Diagrams, Primitive Types,                                 |                                             |
| 6    | 46 | Tue, 2015-11-17 | Object Types, Multiple Constructors, Debugger                                                | [Exercise 04](../labs/exercise-04.html)     |
|      |    | Thu, 2015-11-19 | Collections, Generics, for-each, While Loops                                                 |                                             |
| 7    | 47 | Tue, 2015-11-24 | More Loops, Iterators, Arrays, For Loops,                                                    | [Exercise 05](../labs/exercise-05.html)     |
|      |    | Thu, 2015-11-26 | Library Classes, Reading Class Documentation, Random, Packages, Maps                         |                                             |
| 8    | 48 | Tue, 2015-12-01 | Public vs. Private, Interfaces, Class Variables                                              | [Exercise 06](../labs/exercise-06.html)     |
|      |    | Thu, 2015-12-03 | Writing Class Documentation, Unit Testing, Test Automation                                   |                                             |
| 9    | 49 | Tue, 2015-12-08 | Modularization, Interfaces, Debugging, Walkthroughs                                          | [Exercise 07](../labs/exercise-07.html)     |
|      |    | Thu, 2015-12-10 | Designing Classes, Coupling, Cohesion, Refactoring                                           |                                             |
| 10   | 50 | Tue, 2015-12-15 | Refactoring                                                                                  | [Exercise 08](../labs/exercise-08.html)     |
|      |    | Thu, 2015-12-17 | Refactoring                                                                                  |                                             |
| 11   | 51 | Tue, 2015-12-22 | Using the main, Inheritance, Subtyping, Polymorphism, Protected                              | [Exercise 09](../labs/exercise-09.html)     |
| ---  | -- | Thu, 2016-12-24 | --------------------------- CHRISTMAS!   ---------------------------------                   | ------------------------                    |
| 12   | 1  | Tue, 2016-01-05 | Welcome to the new year: Repetition                                                          | [Exercise 10](../labs/exercise-10.html)     |
|      |    | Thu, 2016-01-07 | Using the main, Inheritance, Subtyping, Polymorphism, Protected                              |                                             |
| 13   | 2  | Tue, 2016-01-12 | Casting, Polymorphism, Static vs. dynamic typing, Overriding, Object equality                | [Exercise 11](../labs/exercise-11.html)     |
|      |    | Thu, 2016-01-14 | Abstract Classes, Abstract Methods, A word about the Exam                                    |                                             |
| 14   | 3  | Tue, 2016-01-19 | Multiple Inheritance vs. Java Interfaces,  GUIs, AWT and Swing, Event handler                | [Exercise 12](../labs/exercise-12.html)     |
|      |    | Thu, 2016-01-21 | An Example: The Image Viewer                                                                 |                                             |
| 15   | 4  | Tue, 2016-01-26 | Errors, Exceptions, Assertions                                                               | tbd                                         |
|      |    | Thu, 2016-01-28 | File-based IO, Files                                                                         |                                             |
| 16   | 5  | Tue, 2016-02-02 | Exam Preparation                                                                             | Trial Exam                                  |
|      |    | Thu, 2016-02-04 | No Lecture, maybe Q&A with a Tutor?                                                          |                                             |
| 17   | 6  | Tue, 2016-02-09 | Exam                                                                                         | Exam                                        |
|      |    | Thu, 2016-02-11 | Klausureinsicht                                                                              |                                             |
t sta


{% comment %}

File, Switch, Exceptions Again
d = Date.new(2015,10,13);(1..18).to_a.collect{|i| [(d+(7*(i-1))).strftime("|#{i} | #{i+40} | %a, %Y-%m-%d |"),(d+(7*(i-1))+2).strftime("|   |    | %a, %Y-%m-%d |") ] }.flatten.each{|x| puts x}

{% endcomment %}