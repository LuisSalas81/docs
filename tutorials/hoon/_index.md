+++
title = "Hoon"
weight = 1
sort_by = "weight"
template = "sections/docs/chapters.html"
aliases = ["/docs/byte/0/", "/docs/byte", "/docs/learn/hoon/hoon-tutorial/"]
+++

This series is designed to teach you Hoon without assuming you have an extensive programming background.  In fact, you should be able to follow much of it even if you have no programming experience at all, though of course experience helps.  We strongly encourage you to try out all the examples of each lesson.  These lessons are meant for the beginner but they aren't meant to be skimmed. Each lesson falls into one of two categories: **readings**, which are prose-heavy explanations of Hoon fundamentals, and **walkthroughs**, which are line-by-line explanations of example programs. Walkthroughs are found between readings, offering a practical implementation of the concepts taught in the reading before.

Chapter 1 introduces and explains the fundamental concepts you need in order to understand Hoon's semantics.

Hoon is a 'subject-oriented' programming language -- every expression of Hoon is evaluated relative to a **subject**.  The subject is a piece of data that represents the environment, or the context, of an expression.  After reading Chapter 1 you should understand what the subject is and how to refer to its various parts.  In this chapter you'll also learn about **cores**, which are an important data structure in Hoon.  Once you get the hang of cores you'll be able to write your own functions in Hoon.

Chapter 2 covers the type system, and writing apps, and the workings of the Arvo kernel.


## Lessons

### Chapter 1

- [1.1 Setup](setup)
- [1.1.1 Walkthrough: List of Numbers](list-of-numbers)
- [1.2 Nouns](nouns)
- [1.3 Hoon Syntax](hoon-syntax)
- [1.3.1 Walkthrough: Conditionals](conditionals)
- [1.4 Gates (Hoon Functions)](gates)
- [1.4.1 Walkthrough: Recursion](recursion)
- [1.5 Lists](lists)
- [1.5.1 Walkthrough: Fibonacci Sequence](fibonacci)
- [1.6 The Subject and Its Legs](the-subject-and-its-legs)
- [1.6.1 Walkthrough: Ackermann Function](ackermann)
- [1.7 Arms and Cores](arms-and-cores)
- [1.7.1 Walkthrough: Caesar Cipher](caesar)
- [1.8 Doors](doors)
- [1.8.1 Walkthough: Bank Account](bank-account)
- [1.9 Generators](generators)

### Chapter 2

- [2.1 Atoms, Auras, and Simple Cell Types](atoms-auras-and-simple-cell-types)
- [2.2 Type Checking and Type Inference](type-checking-and-type-inference)
- [2.3 Structures and Complex Types](structures-and-complex-types)
- [2.3.1 Walkthrough: Libraries](libraries)
- [2.4 Standard Library: Trees, Sets, and Maps](trees-sets-and-maps)
- [2.5 Type Polymorphism](type-polymorphism)
- [2.5.1 Walkthrough: Iron Polymorphism](iron-polymorphism)
- [2.5.2 Walkthrough: Lead Polymorphism](lead-polymorphism)
- [2.6 Gall](gall)
- [2.7.1 Walkthrough: Egg Timer](egg-timer)
- [2.7.2 Gall: Async Monad](async-monad)
- [2.8 Ford](ford)
- [2.8.1 Walkthrough Ford Testing Suite Walkthrough](test-sets)
- [2.9.1 Walkthrough: Landscape Tile](landscape-tile)


## Other Resources

Want to know how to style your code? Check out the [style guide](style).

Consult the [standard library documentation](@/docs/reference/library/_index.md) or [rune reference](@/docs/reference/hoon-expressions/_index.md) to look up any unknown rune or standard library function you don't understand.

As you work your way through these lessons you may want to work on example problems from the [Hoon Workbook](@/docs/tutorials/hoon/workbook/_index.md) for practice.  Once you finish the lessons here you may want to write more versatile Hoon programs which can make use of more of your urbit's environment, in which case you'll want to check out the [Generators](@/docs/tutorials/hoon/generators.md) documentation. Learn about [Udon and Sail](@/docs/tutorials/sail-and-udon.md), Urbit's stripped-down version of Markdown, and a subset of Hoon used for generating XML nodes respectively.


> Last major revision of this section: November 2019
