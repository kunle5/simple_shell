# C - simple_shell

# Authors

Abdul-Hafiz Aderemi
Israel Israel

# Overview
Sodash is a sh-compatible command language interpreter that executes commands read from the standard input or from a file. Sodash is a simple shell unix command interpreter that is part of the alx low level programming module at Alx School and is intended to emulate the basics sh shell

# Invocation
Usage: Sodash Sodash is started with the standard input connected to the terminal. To start, compile all .c located in this repository by using this command: gcc -Wall -Werror -Wextra -pedantic *.c -o sodash ./sodash Sodash is allowed to be invoked interactively and non-interactively. If sodash is invoked with standard input not connected to a terminal, it reads and executes received commands in order.

## **Copyright - Plagiarism**
You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
You are not allowed to publish any content of this project.
Any form of plagiarism is strictly forbidden and will result in removal from the program.

# Requirements
## General
Allowed editors: vi, vim, emacs
All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
All your files should end with a new line
A README.md file, at the root of the folder of the project is mandatory
Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
Your shell should not have any memory leaks
No more than 5 functions per file
All your header files should be include guarded
Use system calls only when you need to (why?)
Write a README with the description of your project
You should have an AUTHORS file at the root of your repository, listing all individuals having contributed content to the repository. Format, see Docker

# More Info
## Output
* Unless specified otherwise, your program must have the exact same output as sh (/bin/sh) as well as the exact same error output.
* The only difference is when you print an error, the name of the program must be equivalent to your argv[0] (See below)
