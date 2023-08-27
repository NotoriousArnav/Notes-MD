# Introduction To C

| Title| Author| Date|
| ----- | ----- | ------ |
| Introduction To C|[@ApurvaPradhan](https://github.com/ApurvaPradhan)|   26 August, 2023 |

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed the latest version of [Visual Studio Code](https://code.visualstudio.com/download)
- You have installed a [Compiler](https://sourceforge.net/projects/mingw/).
- For a detailed guide you can use [reference](https://medium.com/@abhinavsinha_/setting-up-visual-studio-code-for-c-c-on-windows-d02ede716280).


##  1. What exactly is C, and why is it important for us to learn?
C is a procedural programming language initially developed by Dennis Ritchie in the year 1972 at Bell Laboratories of AT&T Labs. It was mainly developed as a system programming language to write the UNIX operating system.

If a person learns C programming first, it will help him to learn any modern programming language as well. As learning C help to understand a lot of the underlying architecture of the operating system. Like pointers, working with memory locations, etc.
## 2. Basic Structure of a C program

  ### Hello, World

  

```c

#include <stdio.h>

  

int main()

{

    //this line will print Hello, World! in the terminal

    printf("Hello, World!\n");

    return 0;

}
```

### Lets break it down

-  **#include <stdio.h>** : This is a preprocessor command that tells the compiler to include the contents of stdio.h (the standard input and output library) in the program. A header file is a file with extension .h which contains C function declarations and macro definitions to be shared between several source files
-   **int main()** : This is the main function where the program execution begins. Here **int** is the return type, **main** is the entry point of the function.
- - **{}** : These curly brackets are used to group all statements of a function. In this case, they're grouping everything under the main function.
- - **printf("Hello, World!\n")** : This is a function that's used to print the string inside the parentheses to the console. Here **\n** is an special character ie an escape sequence. When used inside a string, it causes a line break, essentially moving to the next line.
- - **return 0** : This ends the main() function and returns the value 0, which typically indicates that the program has completed successfully.


## 3. What happens behind the scene during the compilation process

###  
-  **Writing the Code** : You first write the C program using a text editor and save it with a .c extension.

- **Preprocessing** : Preprocessor directives (lines starting with #) are executed first. These include including header files using #include, defining constants using #define, and others.

  
 -  **Compilation** : The compiler takes the preprocessed code and transforms it into assembly code. This process also checks for any syntax errors and whether the code makes sense grammatically to the compiler.

  

-  **Assembly** : The generated assembly code is then converted into machine code (object code) by the assembler. It's a binary file ready to be linked but cannot run on its own yet.

  

- **Linking** : If there are any header files or additional C files referenced, they will be linked together to generate an executable file. The linker takes care of arranging the code and data in memory, resolving symbol references, and relocating code and data as necessary. This creates the final executable.

  

- **Execution** : At this point, the compiled and linked C program (an executable file) can be executed/run. The operating system's loader loads the executable into memory and starts running the program from the 'main' function. The output is then displayed on the console.

  

You can usually see most of these steps happening in your IDE or command line if you're compiling and running your program manually. If you've ever received compile-time or run-time errors, now you know at what phase they occur!
# **Conclusion**


-  Gaining an indepth understanding of how each line of code operates is fundamental to becoming a proficient programmer. 

-  This enables you to write more efficient and effective programs, identify potential issues more quickly, and understand the root causes of bugs at a granular level.

- These skills not only improve the performance of your code but also facilitate meaningful collaboration and communication in team-based projects.