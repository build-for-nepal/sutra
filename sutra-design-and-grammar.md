> This document provides a high level overview of the design and the grammar of *sutra* programming language.

_WORK IN PROGRESS_

## Goal

The primary goal of "sutra" is to provide a step by step guide for students and enthusiasts
to learn basics of designing a programming language from scratch.

This repo will be setup as a series of steps, all separated by branches
that will allow you to incrementally go through the design process.

## Core Concepts, Assumptions and Constraints

- Syntax based on Nepali language
- Static Typing
- Limited grammar, all Nepali words
- Imperative paradigm
- We will treat this language as a happy baby and keywords of verbal kind will use polite form of speech (`तिमी`)

## Basic Syntax and Structure

- "newline" indicates end of each statement
- indentation to structure blocks (similar to python)
- basic comment support with `#`

## Grammars

### Keywords and Operators

| Title                    | Keyword Term    | Remarks                                       |
|--------------------------|-----------------|-----------------------------------------------|
| Variable declaration     | maana           | Used to declare variables                     |
| Function definition      | kaarya          | Used to define functions                      |
| If statement             | yedi            | Begins an if condition                        |
| Else statement           | natra           | Used in if-else constructs                    |
| While loop               | jabasamma       | Begins a while loop                           |
| For loop                 | laagi           | Begins a for loop                             |
| Return                   | farkaau         | Returns a value from a function               |
| And                      | ra              | Logical AND operator                          |
| Or                       | wa              | Logical OR operator                           |
| Not                      | haina           | Logical NOT operator                          |
| True                     | satya           | Boolean true value                            |
| False                    | asatya          | Boolean false value                           |
| Null                     | lupta           | Represents null or empty value                |
| Print                    | dekhau          | Function to output to console                 |
| Integer type             | anka            | Declares an integer variable                  |
| Float type               | dashmalab       | Declares a float variable                     |
| Character type           | akshar          | Declares a character variable                 |
| String type              | paath           | Declares a string variable                    |
| Boolean type             | satyata         | Declares a boolean variable                   |
| Addition                 | joda            | Addition operator                             |
| Subtraction              | ghatau          | Subtraction operator                          |
| Multiplication           | guna            | Multiplication operator                       |
| Division                 | bhaaga          | Division operator                             |
| Modulus                  | shesh           | Modulus operator                              |
| Equal to                 | samaan          | Equality comparison operator                  |
| Not equal to             | asamaan         | Inequality comparison operator                |
| Less than                | sano            | Less than comparison operator                 |
| Greater than             | thulo           | Greater than comparison operator              |
| Less than or equal to    | sano-saman      | Less than or equal to comparison operator     |
| Greater than or equal to | thulo-samaan    | Greater than or equal to comparison operator  |
