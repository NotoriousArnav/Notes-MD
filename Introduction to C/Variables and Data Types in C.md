# Variables and Data Types in C - BCA 1st Semester Notes

In this tutorial, we'll provide comprehensive notes on variables and data types in C for BCA 1st-semester students. Understanding these fundamental concepts is crucial for a strong foundation in programming.

## Introduction to Variables

- **Definition**: Variables are names given to specific memory locations used to store data.

### Declaration of Variables

- **Syntax**: `data_type variable_name;` or `data_type variable_name = value;`
- The data type determines what kind of data the variable can store (e.g., int, float, char).

### Naming Conventions for Variables

- A variable name can consist of alphabets, digits, and underscores (-).
- It must start with an alphabet, not a digit.
- No white spaces are allowed.
- Variable names cannot be reserved keywords or contain special characters.

## Assigning Values to Variables

- Variables can be assigned values in two ways: 
   1. `data_type variable_name = value;`
   2. `data_type variable_name; variable_name = value;`

### Example 1:

```c
int a = 12;
```

### Example 2:

```c
int a;
a = 12;
```

## Data Type Restrictions

- Variables are type-specific; they can only store data of their declared type.
- For example, an integer variable can only store integer values; it cannot store characters or decimals.

### Example 1:

```c
int a = 12.2221; // Here, the value 12.2221 will be truncated to 12.
```

### Example 2:

```c
float a = 12.2221; // In this case, the value 12.2221 will be stored as is.
```

- Note the use of `%f` for printing float variables and `%d` for integers.

## Common Data Types in C

- C provides various data types with different memory requirements and value ranges:

| Data Type          | Memory (Bytes)  | Range                  |
|--------------------|-----------------|------------------------|
| Char               | 1               | -128 to 127            |
| Signed Char        | 1               | -128 to 127            |
| Unsigned Char      | 1               | 0 to 255               |
| Short Int          | 2               | -32,768 to 32,767      |
| Unsigned Short Int | 2               | 0 to 65,535            |
| Unsigned Int       | 4               | 0 to 65,535            |
| Int                | 2               | -32,768 to 32,767      |
| Long Int           | 4               | -2,147,483,648 to 2,147,483,647 |
| Unsigned Long Int  | 4               | 0 to 4,294,967,295     |
| Float              | 4               |                        |
| Double             | 8               |                        |
| Long Double        | 10              |                        |

These notes provide a solid foundation in variables and data types, essential for BCA 1st semester students starting their programming journey in C.