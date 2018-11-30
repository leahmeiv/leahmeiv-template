---
layout: essay
type: essay
title: "Final Project Idea"
date: 2018-11-29
labels:
  - Software Engineering
  - Design Patterns
---

A common interview question is “What are design patterns?”, followed by “What design patterns have you used in your own code?”

For this technical essay, you will write an interesting and informative technical essay that ends up answering these two
questions. By doing so, you’ll be better prepared to answer this question if it comes up in an interview.

Do not, under any circumstances, write two paragraphs, one with the title “What are design patterns?” and one with the title 
“How I have used them in my code.” That will get you no points, as such an essay would be too boring for anyone to read.

Instead, write an essay, perhaps using metaphor or analogy, which by its conclusion has answered these two questions but 
in a clever, interesting, and informative fashion.


Notes
a design pattern describees a bproblem that occurs over and over again in our environment and then describes the core of the solution to that problem in such a way that you can use this soltution a million times over without ever doing it the same way twice.

Example: design pattern of roofs

Design patterns in software developement
- Design patterns are a general reusuable solution to a commonly occuring problem in software design
- a design patttern in a template that can be used in many different situations
- OO Design Patterns show relationships and interactions between classes or objects without satisfying the final application classes or object

Describging a design pattern
- Name: meaning ful descriptor
Problem description:
- When to apply the patter
Solution description:
- The classes, objects, etc. and their relationships
Consequences
-Trade offs of using that pattern
Factory Problem Description
- Create objects without exposing underlying logic potentially returning objects associated with different classes, and or creating dependent objects
Advantages over OO class constructor
-can return objects from different classes
-return multiple objects
-can build additional dependent objects
Disadvantages
-More complicated than OO class constructor

Singleton Problem description
- Provide a global variable in an object oriented language that deos not support global variables and provide complex global site

Advntantages
- provides glpbal state in an pbject oriented manner
- easy to implement lazy initialization
Disadvantages 
-not normally thread safe
- global state is often unwise

Observer problem description
- When a set of objects (observers) need to be informed whenever a change in state occurs to another object (subject)
- This is a common scenario in event driven systems when you need to provide one or more event handlers

Observer Consequences
Advantages
- define a one to many dependency without tight coupling
- allows open ended numbers of dependencies
- allows dependencies to change at run time
Disadvantages
- Poor implementations can lead to performance issues
- Can lead to race conditions in multi-threaded systems
- Can be harder to reason about and debug

Model View controller 
- When implementing a user interface, it is desirable to decouple the internal representation of information from the way it is presented to and accepted from the user
Advantages
- This specific partitioning of responsibilities fascilitates concurrent developement by people with different skill sets (view by interface specialist, model by DB specialistm etc)
- Low coupling between components
- A model can have multiple views
Disadvantages
-COmplexity and learning curve

Antipatterns
- Commonly occuring solutions to probalmes with decidedly negative consequences
- Manager doesn't know any better
-Not enough experience
- Apllying a good pattern in wrong context
- Example: Lava flow.. dead code and forgotten design information is frozen in a changing implementation, similar to how molten lava turns to rock
