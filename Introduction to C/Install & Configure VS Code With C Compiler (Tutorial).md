## Understanding IDE and Compiler

- **IDE**: Stands for Integrated Development Environment. It's an advanced text editor that helps you write efficient code by highlighting syntax and providing error notifications. For this tutorial series, VS Code is recommended.
    
- **Compiler**: It's essential for running code by converting it into a language the computer can understand. Each programming language requires a specific compiler. In this course, MinGW is recommended and used.

## Installation Steps

### Visual Studio Code Installation

1. Visit [VS Code download](https://code.visualstudio.com/download).
    
2. Click on the download option.
    
3. Run the downloaded setup, keeping the default settings.
    
4. After installation, run VS Code.
    

### MinGW Installation

1. Search for "C programming in VS Code" on Google or visit [this URL](https://code.visualstudio.com/docs/languages/cpp).
    
2. Select C++ from the sidebar.
    
3. Choose "GCC via Mingw-w64 on Windows."
    
4. You'll be redirected to a page; select "install sourceforge option."
    
5. After download, run the setup, and choose default options.
### Setting Path for Compiler

1. Navigate to C directory → Program Files → mingw-64 → mingw-32 → bin.
    
2. Save the path or URL to the bin directory.
    
3. Go to "This PC" properties → "Advanced System Settings" → "Environment Variable."
    
4. Add the copied bin path to Environment variables.

Now, you can use your IDE to run C code.

**Note**: If you encounter a "gcc is not recognized" error, there's an [additional tutorial](https://www.youtube.com/watch?v=qLh84CmdBJ0) provided in the blog.

## Sample Code

Here's a simple C code snippet

```c
#include <stdio.h>
int main(){
	printf("Hello World\n");
	return 0;
}
```