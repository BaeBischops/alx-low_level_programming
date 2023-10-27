# ALX Low-Level Programming - Printf Project

Welcome to my ALX Low-Level Programming "printf" project repository! This repository contains my implementation of the `printf` function in C, which is a significant project that showcases my understanding of low-level programming and the intricacies of formatting and printing text in C.

## Table of Contents

1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [File Structure](#file-structure)
4. [How to Compile and Use](#how-to-compile-and-use)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction

The `printf` project is a fundamental part of the ALX Low-Level Programming curriculum. It involves the creation of a custom version of the `printf` function that can format and print text to the standard output. Completing this project is a significant milestone and demonstrates a deep understanding of C programming, string manipulation, and memory allocation.

This repository serves as a showcase of my "printf" project. Feel free to explore the source code, review the implementation, and see how I approached this challenging task.

## Project Overview

The "printf" project implements a simplified version of the `printf` function found in the C Standard Library. It is responsible for formatting and printing text to the standard output, just like the real `printf` function.

My implementation supports various format specifiers, such as `%c` (character), `%s` (string), `%d` (decimal integer), `%i` (integer), `%u` (unsigned integer), `%x` (hexadecimal), `%X` (uppercase hexadecimal), `%o` (octal), and more.

The code is organized and structured to handle different format specifiers, flags, and modifiers, making it a comprehensive and functional `printf` implementation.

## File Structure

The project directory is organized as follows:

- `holberton.h`: A custom header file containing function prototypes and necessary includes.
- `*.c` files: The source code files for the `printf` function and its supporting functions.
- `man_3_printf`: A manual page providing information on how to use the `printf` function.

Feel free to explore the source code to see how the `printf` function and its supporting functions are implemented.

## How to Compile and Use

To compile and use the `printf` function:

1. Clone this repository to your local machine.

2. Navigate to the project directory.

3. Compile the code using your preferred C compiler (e.g., GCC):

   ```bash
   gcc -Wall -Werror -Wextra -pedantic *.c -o my_printf

