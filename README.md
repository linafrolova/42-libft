# 42-libft

![42 Logo](https://www.42.us.org/wp-content/uploads/2019/02/42_logo_white.png)

## Table of Contents
- [Introduction](#introduction)
- [What's in the Library](#whats-in-the-library)
  - [Functions from `<ctype.h>`](#functions-from-ctypeh)
  - [Functions from `<string.h>`](#functions-from-stringh)
  - [Functions from `<stdlib.h>`](#functions-from-stdlibh)
  - [Non-standard Functions](#non-standard-functions)
  - [Linked List Functions](#linked-list-functions)

## Introduction

Libft is a project at School 42 that requires you to recreate some standard C library functions, as well as additional functions to use throughout your future projects at 42.

## What's in the Library

Here are some of the functions implemented in the Libft library:

## Functions from `<ctype.h>`

- **`ft_isalpha`**
  - Checks for an alphabetic character.

- **`ft_isdigit`**
  - Checks for a digit (0 through 9).

- **`ft_isalnum`**
  - Checks for an alphanumeric character.

- **`ft_isascii`**
  - Checks whether the character fits into the ASCII character set.

- **`ft_isprint`**
  - Checks for any printable character.

- **`ft_toupper`**
  - Converts a character to uppercase.

- **`ft_tolower`**
  - Converts a character to lowercase.

## Functions from `<string.h>`

- **`ft_strlen`**
  - Calculates the length of a string.

- **`ft_memset`**
  - Fills memory with a constant byte.

- **`ft_bzero`**
  - Zeros a byte string.

- **`ft_memcpy`**
  - Copies a memory area.

- **`ft_memmove`**
  - Copies a memory area.

- **`ft_strlcpy`**
  - Copies a string to a specific size.

- **`ft_strlcat`**
  - Concatenates a string to a specific size.

- **`ft_strchr`**
  - Locates a character in a string.

- **`ft_strrchr`**
  - Locates a character in a string.

- **`ft_strncmp`**
  - Compares two strings.

- **`ft_memchr`**
  - Scans memory for a character.

- **`ft_memcmp`**
  - Compares memory areas.

- **`ft_strnstr`**
  - Locates a substring in a string.

- **`ft_strdup`**
  - Creates a duplicate for the string passed as a parameter.

## Functions from `<stdlib.h>`

- **`ft_atoi`**
  - Converts a string to an integer.

- **`ft_calloc`**
  - Allocates memory and sets its bytes' values to 0.

## Non-standard Functions

- **`ft_substr`**
  - Returns a substring from a string.

- **`ft_strjoin`**
  - Concatenates two strings.

- **`ft_strtrim`**
  - Trims the beginning and end of a string with a specific set of characters.

- **`ft_split`**
  - Splits a string using a character as a parameter.

- **`ft_itoa`**
  - Converts a number into a string.

- **`ft_strmapi`**
  - Applies a function to each character of a string.

- **`ft_striteri`**
  - Applies a function to each character of a string.

- **`ft_putchar_fd`**
  - Outputs a character to a file descriptor.

- **`ft_putstr_fd`**
  - Outputs a string to a file descriptor.

- **`ft_putendl_fd`**
  - Outputs a string to a file descriptor, followed by a new line.

- **`ft_putnbr_fd`**
  - Outputs a number to a file descriptor.

## Linked List Functions

- **`ft_lstnew`**
  - Creates a new list element.

- **`ft_lstadd_front`**
  - Adds an element at the beginning of a list.

- **`ft_lstsize`**
  - Counts the number of elements in a list.

- **`ft_lstlast`**
  - Returns the last element of the list.

- **`ft_lstadd_back`**
  - Adds an element at the end of a list.

- **`ft_lstclear`**
  - Deletes and frees a list.

- **`ft_lstiter`**
  - Applies a function to each element of a list.

- **`ft_lstmap`**
  - Creates a new list resulting from a successive appliction of a funtion f. 
