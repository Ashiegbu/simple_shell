# Simple_Shell  project 
**ALX Software Programm** paired team project 
This is a simple UNIX command interpreter based on bash and Sh.

## Overview

Sodashy is a sh-compatible command language interpreter that executes commands read from the standard input or from a file.
Invocation

Usage: Sodash Sodash is started with the standard input connected to the terminal. To start, compile all .c located in this repository by using this command:

gcc -Wall -Werror -Wextra -pedantic *.c -o sodash
./sodash

Sodash is allowed to be invoked interactively and non-interactively. If sodash is invoked with standard input not connected to a terminal, it reads and executes received commands in order.

Project done during **Full Stack Software Engineering studies** at **ALX Software Programm**. It aims to learn about how to handle files (open, close, read and write), file descriptors, system calls and file permissions in **C language**.

## Technologies
* C files are compiled using `gcc 4.8.4`
* C files are written according to the C90 standard
* Tested on Ubuntu 20.04 LTS
* Allowed editors: vi, vim, emacs
* All your files should end with a new line
* A README.md file, at the root of the folder of the project is mandatory
* Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl   
* Your shell should not have any memory leaks   
* No more than 5 functions per file  
* All your header files should be include guarded,Use system calls only when you need to (why?)
* Write a README with the description of your project  
* You should have an AUTHORS file at the root of your repository, listing all individuals having contributed content to the repository. Format, see Docker
    
## Files
All of the following files are programs written in C:

| Filename | Description |
| -------- | ----------- |
|`aux_error1.c` | Function that concatenates the message for cd error |
|`aux_error2.c` | Function that Auxilary modifiers the message for cd error |
|`aux_help.c `  | Adding logic operators, help builtin  |
|`aux_lists.c ` | adding replacement of variables and fixing aux_help_env - Help information for the builtin |
|`aux_lists2.c` | Function that makes head of the linked list |
|`aux_mem.c `   | memcpy - copies information between void pointers.|
|`aux_stdlib.c `| Function that makes standard library |
|`aux_str.c `| Function that makes standard library |
|`aux_str2.c `| Function that makes standard library |
|`aux_str3.c `|adding cd builtin |
|`cd.c `| shell works without OLDPWD and PWD |
|`cd_shell.c `|'cd_shell -' changes current directory |
|'check_syntax_error.c'|counts the repetitions of a char,logic operators|
|'cmd_exec.c'| the current directory,works when there is no PATH|
|'env1.c'|adding setenv function and fix error messages|
|'env2.c'| adding cd builtin|
|'exec_line.c'|fix error functions and get_error|
|"exit_shell.c'|adding setenv function and fix error messages|
|'get_builtin.c|help builtin and comments|
|`get_error.c `|modified case error permission 126 |
|`get_help.c `|dding logic operators, help builtin and comments  |
|`get_line.c `|adding read, parse and execute process of Shell  |
|`get_sigint.c `| added get_sigint.c function that handles crt +c |
|`main.c `| Executive files |
|`man_1_simple_shell `| man 1 simple shel |
|`read_line.c `|read_line - reads the input string. |
|`rep_var.c `|check_env - checks if the typed variable is an env variable  |
|`shell_loop.c `| without_comment - deletes comments from the input |
|`split.c `|replacement of variables and fixing Operators |
|`main.h `| Main shell executes files Headers |

AUTHORS 
Chibuzo Ashiegbu
Kingsley Emeka Umunna
