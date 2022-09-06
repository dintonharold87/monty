# :snake: Monty Interpreter

Welcome to the Monty Bytecode Interpreter. This interpreter was built in the C language and is compliant with `ISO90`, `ISO99`, & `ISO11`. It reads Monty bytecode files of any extension (preferably `.m` although it doesn't matter), and interprets the opcodes contained.

Our interpreter can be run as either a stack (LIFO) or queue (FIFO). Mode can be switched mid-script. The interpreter can handle a variety of Monty opcodes, including printing, mathematical operations, and more - all handled opcodes are listed below.

## :running: Getting Started

* [Ubuntu 20.04 LTS](http://releases.ubuntu.com/20.04/) - Operating system reqd.




## :arrow_down: Installing and Using

Clone the repository into a new directory:

```
$ git clone the repository
```
Compile with the following:

```
gcc -Wall -Werror -Wextra -pedantic *.c -o monty
```

Run the interpreter on a file:

```
./monty file.m
```

## Table of contents

File | Description
---- | -----------
[main.c](./main.c) | entry point of the program
[monty.h](./monty.h) | main header file
[lists.h](./lists.h) | header file for the lists functions
[get_func.c](./get_func.c) | function that picks the right function for the instruction
[list_funcs1.c](./list_funcs1.c) | doubly linked list functions
[list_funcs2.c](./list_funcs2.c) | doubly linked list functions
[strtow.c](./strtow.c) | string tokenizing functions
[free.c](./free.c) | memory handling functions

