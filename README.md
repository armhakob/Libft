# Libft


**Libft** is a custom implementation of a standard C library, designed as part of the 42 curriculum. This project involves recreating many commonly used functions from the C standard library, along with additional utility functions to handle strings, memory, lists, and more.

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)

## About the Project

The goal of **Libft** is to create a robust foundation of reusable C functions that can be used in various other projects. Through this, programmers strengthen their understanding of low-level programming, memory management, and algorithm implementation.

This project adheres to the strict coding guidelines and standards of the 42 Network.

## Features

### Part 1: Standard C Library Functions

- **String manipulation**: `ft_strlen`, `ft_strcpy`, `ft_strcmp`, etc.
- **Memory handling**: `ft_memset`, `ft_memcpy`, `ft_bzero`, etc.
- **Character checks**: `ft_isalpha`, `ft_isdigit`, `ft_tolower`, etc.

### Part 2: Additional Functions

- String splitting (`ft_split`)
- Conversion utilities (`ft_itoa`, `ft_atoi`)
- Memory allocation and cleanup (`ft_calloc`, `ft_strdup`)

### Bonus: Linked List Functions

- `ft_lstnew`
- `ft_lstadd_front`, `ft_lstadd_back`
- `ft_lstdelone`, `ft_lstclear`

## Getting Started

### Prerequisites

- A C compiler (GCC or Clang)
- GNU Make

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/armhakob/Libft.git
   cd Libft
2. Compile the library:
   ```bash
   make
3. The compiled libft.a file will be generated in the root directory.


### Usage

Compile your program with:
  ```bash
  gcc -Wall -Wextra -Werror your_program.c libft.a -o your_program
