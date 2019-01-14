Following the IPL schedule

## Day 1
### 1
In C, if a function signature doesn’t specify any argument, it means that the function can be called with any number of parameters or without any parameters. But, it's not the case in C++ . The same thing holds good for user defined functions as well.

```c
int main() /*Better to use int main(void)*/
{ 
   /* .... */
   return 0; 
}
```
[Link for GFG site](https://www.geeksforgeeks.org/difference-int-main-int-mainvoid/)

### 2
Preprocessors in C/C++ :
- 'include' in the top of the c file will include all the required standard source code into our file
- <stdio.h> asks the system to loof for files from the standard source ile folder. 
- "lengthy.h" asks the system to look into current folder for source code.
- Macros can have arguments, they will be acting like a templates. (We can pass any data type)
- Macros can be made into multiple lines by adding '\' at the end of each line. (Not for the last line)
- Tokens passed to macros can be concatenated using operator ## called _Token-Pasting operator_. 
```c
#include <stdio.h> 
#define merge(a, b) a##b 
int main() 
{ 
    printf("%s", merge(Akbar,Microsoft)); 
} 
// Output: AkbarMicrosoft
```
- Some standard default macros __FILE__, __DATE__, __TIME__, __LINE__  gives some basic details of the program.
- Any macro can be un-defined using #undef macro_name. After the undef statment in the code, the macro wont work.
[Link for GFG Site](https://www.geeksforgeeks.org/interesting-facts-preprocessors-c/)

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
