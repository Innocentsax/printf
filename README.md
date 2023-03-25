<p align="center">
<img src="https://www.techrepublic.com/wp-content/uploads/2022/07/top-ide-software.jpeg">
</p>

### TEAM PROJECT ON PRINTF
___
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/Innocentsax/standard-readme)

The "printf" project is a programming exercise that is commonly used in introductory computer science courses to help students learn the basics of the C programming language. The goal of the project is to create a function that can print formatted output to the console. The printf function is a powerful tool that can be used to display strings, numbers, and other data types in a variety of ways.

***More detail***

In the printf project, students are tasked with creating a simplified version of the printf function, which can handle a limited set of formatting options. The function takes a format string as input, which specifies how the output should be formatted, and a variable number of arguments, which contain the data to be printed. The function then processes the format string and outputs the formatted data to the console.

The printf project is a valuable learning experience for students, as it helps them develop their programming skills and gain a deeper understanding of how programming languages work. By completing the project, students learn about C syntax, string manipulation, memory allocation, and other important programming concepts.

## Evironment
- Language: C
- Editor: VIM 8.1.2269
- Compiler: gcc 9.3.0
- Wall -Werror -Wextra -pedantic -std=gnu89
- Style guidelines: [Betty style](https://github.com/holbertonschool/Betty/wiki)

## Project specifitacation

- No allowed to use global variable
- No more than 5 functions per file
- All files end with a new line

<h3>Specifiers </h3>
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
|printf_flowchart.png | flowchart _printf|

## Install
To install execute in terminal
git clone https://github.com/Innocentsax/printf


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

## Compilation
All files were compiled on Ubuntu 14.04 LTS.

All programs and functions were compiled with `gcc 4.8.4` using flags `-Wall -Werror -Wextra and -pedantic`.

## Styling
All files have been written in the Betty Style.

## Authors
© **INNOCENT UDO** - [Github Account](https://github.com/Innocentsax) Email:[innocentcharlesud@gmail.com](mailto:innocentcharlesudo@gmail.com)
<!--
© **PIUS OWOLABI** - [Github Account](https://github.com/opius2017) Email: [opius2007@gmail.com](mailto:opius2007@gmail.com)
-->
