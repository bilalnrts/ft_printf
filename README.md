# ft_printf

This project is an attempt to recreate the printf function in C language. The printf function is a C library function that writes formatted data to the standard output stream (stdout) according to a given format. This project aims to mimic the basic functionality and some additional features of the printf function.

## Installation
To use this project, follow these steps:

- Clone this repository to your local machine :
```javascript
git clone https://github.com/bilalnrts/ft_printf.git
```
- Run the Makefile :
```javascript
make
```
- Link the created libftprintf.a library to your desired program :
```javascript
gcc -L. -lftprintf main.c
```

## Usage
In this project, the following format specifiers are supported for the printf function :
- c: Prints a character
- s: Prints a string of characters
- p: Prints a pointer address
- d: Prints a decimal integer
- i: Prints a decimal integer
- u: Prints an unsigned decimal integer
- x: Prints an unsigned hexadecimal integer
- X: Prints an unsigned hexadecimal integer

## Examples 
```javascript
#include "ft_printf.h"

int main(void)
{
    ft_printf("The best number is %d.\n", 42);
    ft_printf("The best string is %s.\n", "Ecole");
    return (0);
}
```
