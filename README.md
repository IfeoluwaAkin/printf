
# _printf

Hello, welcome to our first group project, we're replicated the printf() fucntion from the C Standard Library.


## Description
The _printf() function produces output according to a format which is described
below. This function write its output to the stdout, the standard output stream. Returns the count of printed characters when the function is successful and -1 when the function fails.

The available convertion specifiers are:
+ %c: Prints a single character.
+ %s: Prints a string of characters.
+ %d: Prints integers.
+ %i: Prints integers.
+ %b: Prints the binary representation of an unsigned decimal.
+ %u: Prints unsigned integers
+ %x: Prints the hexadecial representation of an unsigned decimal in lowercase letters
+ %X:Prints the hexadecial representation of an unsigned decimal in uppercase letters
+ %r: Prints a reversed string
+ %R: Prints the Rot13 interpretation of a string

### version 1.0

## Introduction to the project

Project _printf() - Produce output to stdout according to a format described below similar to the printf() function.

## Evironment
- Language: C
- Editor: VIM 8.1.2269
- Compiler: gcc 9.3.0
- Wall -Werror -Wextra -pedantic -std=gnu89
- Style guidelines: [Betty style](https://github.com/holbertonschool/Betty/wiki)

## Project specifitacation

- Not allowed to use global variable
- Not more than 5 functions per file
- All files end with a new line

<h3> Specifiers </h3>
Specifier characters at the end define the type and the interpretation of its corresponding argument:

| Specifier  | Output          |
|------------|-----------------|
| `c`        | character       |
| `s`        | string          |
| `d` or `i` | Signed integer  |
| `%`        | %               |

## Repository files

|**File**|**Description**|
|--------|---------------|
|README.md|this file|
|\_putchar.c|putchar function|
|get_function.c|get_function function|
|main.h|header file|
|print_char.c|print_char function|
|print_digit.c|print_digit function|
|print_string.c|print_string function|
|printf.c|main function|
|man_3_printf | man page|

## Install
To install execute in terminal
git clone https://github.com/IfeoluwaAkin/printf

## Compilation

``gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c``

## EXAMPLES ##
- _printf functions examples:

- _printf("Character:[%c]\n", 'H');
  + Output: char: [H]
- _printf("String:[%s]\n", "I am a string !");
  + Output: string: [I am a string !]
- _printf("decimal: [%d]\n", 10000);
  + Output: decimal: [10000]
- _printf("Percent: [%%]\n");
  + Output: Percent: [%%]
  
  
<br>

# Contributors 

[Theophilus Samuel](https://github.com/ConnectedDot) & [Ife Akinyunni](https://github.com/IfeoluwaAkin).

=======

