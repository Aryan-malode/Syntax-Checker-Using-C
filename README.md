# C-Syntax-Checker 🛠️

![C Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/The_C_Programming_Language_logo.svg/64px-The_C_Programming_Language_logo.svg.png)



C-Syntax-Checker is a program designed to help developers identify common syntax mistakes in their C programs. Whether you're a beginner just learning C or an experienced developer, this tool can be handy in spotting errors quickly.

## Features

- **Bracket Checks**: Ensures proper opening and closing of curly braces.
- **Builtin Function Call**: Detects usage of built-in functions.
- **Prototype Check**: Verifies if function prototypes match their definitions.
- **Keyword Highlighting**: Identifies keywords and highlights them along with their line numbers.
- **Comment and Whitespace Removal**: Cleans up code by removing comments and empty spaces.
- **Keyword Syntax Errors**: Flags common keyword syntax errors such as misuse of `gets`, `printf`, `scanf`, etc.
- **Total Lines Count**: Provides the total number of lines in the code.

## Usage

1. **Input**: Provide your C program file as input to the C-Syntax-Checker.
2. **Analysis**: The program will analyze your code based on the mentioned checks.
3. **Output**: Receive a detailed report highlighting any syntax errors or potential issues found in your code.

## Getting Started

To get started with C-Syntax-Checker, simply download the program from [link_to_repo] and follow the installation instructions in the README.

## Example

```c
#include <stdio.h>

int main() {
    int num = 5;
    if (num > 0) {
        printf("Positive number\n");
    } else {
        printf("Negative number\n");
    }
    return 0;
}
