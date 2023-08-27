# Basic Syntax of a C Program

This tutorial focuses on understanding the fundamental syntax of a C program, essential for BCA 1st-semester students starting their programming journey.

## Components of a C Program

A C program consists of various tokens, which are the building blocks of code. These tokens include:

1. **Keywords**: Reserved words with specific functions, like `return` in the code below.

2. **Identifiers**: Names given to variables or functions, following specific rules, e.g., "a" in the code.

    - Note: C is case-sensitive, so "a" and "A" would be different identifiers.

3. **Constants**: Values that do not change, irrespective of data types. E.g., "0" in the code.

4. **String Literals**: Lines of characters enclosed in double quotes, used for printing text. E.g., "Enter number a."

5. **Symbols**: Special characters with specific functions. For example, "&" is used as a symbol in the code.

## Code Structure

- C programs are structured using various tokens combined together. A few key points regarding code structure:

    - White spaces or blank spaces don't affect the code in C. Unlike Python, where new lines matter, in C, semi-colons (";") are used to end lines of code. Until a semi-colon is encountered, the compiler treats the code as a single line. This means that proper code execution relies on correctness rather than formatting.

### Example 1:

```c
#include <stdio.h>

int main()
{
    printf("Hello World\n");
    return 0;
}
```

### Example 2:

```c
#include <stdio.h>

int main()
{
    printf
    (
    "Hello World\n"
    )
    ;
    return 0;
}
```

Both examples produce the same output, "Hello World," despite differing in white space usage. This underscores the flexibility of C in terms of code formatting.