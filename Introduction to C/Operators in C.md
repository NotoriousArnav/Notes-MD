---
title: Basic Structure of a C Program
author: Arnav ghosh
---
# Operators in C
Operators are essential elements of C programming that allow you to perform various operations on data. 
## Types of Operators

C programming includes several types of operators:

1. **Arithmetic Operators**: These operators perform mathematical operations on numeric operands.
    
    - Examples:
        - `+` (addition)
        - `-` (subtraction)
        - `*` (multiplication)
        - `/` (division)
        - `%` (modulo, remainder)
2. **Relational Operators**: These operators compare two values and return a Boolean result (true or false).
    
    - Examples:
        - `==` (equal to)
        - `!=` (not equal to)
        - `<` (less than)
        - `>` (greater than)
        - `<=` (less than or equal to)
        - `>=` (greater than or equal to)
3. **Logical Operators**: These operators work with Boolean values and perform logical operations.
    
    - Examples:
        - `&&` (logical AND)
        - `||` (logical OR)
        - `!` (logical NOT)
4. **Assignment Operators**: These operators assign values to variables.
    
    - Examples:
        - `=` (assignment)
        - `+=` (add and assign)
        - `-=` (subtract and assign)
        - `*=` (multiply and assign)
        - `/=` (divide and assign)
        - `%=` (modulo and assign)
5. **Increment and Decrement Operators**: These operators increase or decrease the value of a variable by 1.
    
    - Examples:
        - `++` (increment by 1)
        - `--` (decrement by 1)
6. **Bitwise Operators**: These operators perform bit-level operations on integers.
    
    - Examples:
        - `&` (bitwise AND)
        - `|` (bitwise OR)
        - `^` (bitwise XOR)
        - `~` (bitwise NOT)
        - `<<` (left shift)
        - `>>` (right shift)
7. **Conditional (Ternary) Operator**: This operator is a shorthand for an if-else statement.
    
    - Example:
        - `condition ? expression1 : expression2`
8. **Comma Operator**: This operator allows multiple expressions to be separated by commas and evaluates them from left to right.
    
    - Example:
        - `expression1, expression2, expression3`

## Precedence and Associativity

- Operators in C have precedence levels that determine the order in which operations are performed. Operators with higher precedence are evaluated first.
    
- In cases where operators have the same precedence, associativity determines the order of evaluation (left-to-right or right-to-left).
    

## Operator Overloading

- C does not support operator overloading, which means that an operator cannot have multiple meanings based on the context. Each operator has a fixed, predefined behavior.