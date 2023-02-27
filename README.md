# Libft ⚠️ Still under "construction"⚠️

This project its our very first project as a student at 42. We will need to recode a few functions of the C standard library as well as some other utility functions that we will use during our whole cursus.

It was a great project so that from the beginning of the course we are aware of how the functions work. 

## Libft Functions

-ft_isalpha - checks for an alphabetic character.<br />
-ft_isdigit - checks for a digit (0 through 9).<br />
-ft_isalnum - checks for an alphanumeric character.<br />
-ft_isascii - checks whether c fits into the ASCII character set.<br />
-ft_isprint - checks for any printable character.<br />
-ft_toupper - convert char to uppercase.<br />
-ft_tolower - convert char to lowercase.<br />

### Functions from <string.h>

-ft_memcpy - copy memory area.<br />
-ft_memmove - copy memory area.<br />
-ft_memset - fill memory with a constant byte.<br />
-ft_memchr - scan memory for a character.<br />
-ft_memcmp - compare memory areas.<br />
-ft_strlen - calculate the length of a string.<br />
-ft_bzero - zero a byte string.<br />
-ft_strlcpy - copy string to an specific size.<br />
-ft_strlcat - concatenate string to an specific size.<br />
-ft_strchr - locate character in string.<br />
-ft_strrchr - locate character in string.<br />
-ft_strncmp - compare two strings.<br />
-ft_strnstr - locate a substring in a string.<br />
-ft_strdup - creates a dupplicate for the string passed as parameter.<br />

### Functions from <stdlib.h>

-ft_atoi - convert a string to an integer.<br />
-ft_calloc - allocates memory and sets its bytes' values to 0.<br />

### Non-standard functions

-ft_substr - returns a substring from a string.<br />
-ft_strjoin - concatenates two strings.<br />
-ft_strtrim - trims the beginning and end of string with specific set of chars.<br />
-ft_split - splits a string using a char as parameter.<br />
-ft_itoa - converts a number into a string.<br />
-ft_strmapi - applies a function to each character of a string.<br />
-ft_putchar_fd - output a char to a file descriptor.<br />
-ft_putstr_fd - output a string to a file descriptor.<br />
-ft_putendl_fd - output a string to a file descriptor, followed by a new line.<br />
-ft_putnbr_fd - output a number to a file descriptor.<br />

### Linked list functions

-ft_lstnew - creates a new list element.<br />
-ft_lstadd_front - adds an element at the beginning of a list.<br />
-ft_lstsize - counts the number of elements in a list.<br />
-ft_lstlast - returns the last element of the list.<br />
-ft_lstadd_back - adds an element at the end of a list.<br />
-ft_lstclear - deletes and free list.<br />
-ft_lstiter - applies a function to each element of a list.<br />
-ft_lstmap - applies a function to each element of a list.<br />
-ft_lstdelone - Takes a node and frees the memory of the node’s content using the function ’del’ given as a parameter and free the node. The memory of’next’ must not be freed.<br />
-ft_lstmap - Iterates the list ’lst’ and applies the function ’f’ on the content of each node. Creates a new list resulting of the successive applications of the function ’f’. The ’del’ function is used to delete the content of a node if needed..<br />

## Usage

### Requirements
The library is written in C language and thus needs the cc compiler and some standard C libraries to run.

 **- Instructions -**

1. Compiling the library

To compile the library, run:

$ cd path/to/libft && make⚠️

2. Using it in your code

To use the library functions in your code, simply include its header:

#include "libft.h"

⚠️

**-make** without bonus functions.

**-make bonus** to compile with bonuses.

## Final Grade

![image](https://user-images.githubusercontent.com/103336451/221586781-05897821-ba71-44c8-b92c-10cd5d22180d.png)
