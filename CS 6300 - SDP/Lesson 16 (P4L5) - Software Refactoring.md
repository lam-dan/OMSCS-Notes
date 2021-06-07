# Lesson 15

In this lesson we will cover software refactoring in agile development which focuses on code understandability, maintainability, and design. We will also discuss concepts such as fully automated refactoring and _bad smells_ which will allow us to determine when we should perform refactoring.

## Software Refactoring Introduction

What is refactoring? **Refactoring** is an activity in software where the goal is to keep the program readable, understandable, and maintainable.

A key factor is that refactoring should be _behavior preserving_; any refactoring done to a particular piece of software will **not** change functionality. This could be checked but **not** guaranteed by testing.

## Reasons To Refactor

Why should we refactor? We should refactor because of the following:

1. Requirements change
2. Design needs to be improved
3. Sloppiness/laziness creeping into software