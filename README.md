# The-C-programming-language-2nd-notes
Notes and exercises from the book of [K&amp;R](the_c_programming_language_2.pdf)

# Chapter 1: A tutorial introduction
## 1. Getting started
- **Concentrate on the basics**: variables, constants, arithmetic, control flow, functions and the rudiments of input and output.
- **Leaving out the features**: pointers, structures, most of C's rich set of operators, several control-flow statements, and the standard library.

How to compile in linux:

```
sudo apt-get install build-essential
```
Type the following command to see what compiler was installed. You will most likely have the GNU C compiler (gcc) installed.
```
cc --version
```
We need a tex editor: Gedit on linux and OS X, or Nano, Vim,...

**Getting started**

-Create a program in a file ".c" such as hello.c
```C
#include <stdio.h>

main()
{
	printf("Hello world\n");
}
```
-Then we compile it with the following command
```
cc hello.c
```
It will create an executable file called a.out. We can run it by type
```
./a.out
```
or we can run
```
gcc -o hello hello.c
```
It will compile the file hello.c and output (-o) the result to an executable file called hello. To run an executable file, type
```
./file_name
```
