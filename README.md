 simple shell project in the C
This is a colloborative project done in pair of two enginneering students at Alx School.

The Project depicts the use of various functions and system calls

In this project we are tasked with creating our own simple UNIX command interpreter. The program must have the exact same output as sh (/bin/sh) as well as the exact same error output. The only difference is when you print an error, the name of the program must be equivalent to your argv[0].

Example

The shell should work like this in interactive mode:

$ ./hsh

($) /bin/ls

hsh main.c shell.c

($)

($) exit

$

Also like this in non-interactive mode:

$ echo "/bin/ls" | ./hsh

hsh main.c shell.c test_ls_2

$

$ cat test_ls_2

/bin/ls

/bin/ls

$

$ cat test_ls_2 | ./hsh

hsh main.c shell.c test_ls_2

hsh main.c shell.c test_ls_2

$

The following are c file that explain project in details.

1. Write a beautiful code that passes the Betty checks
2. Write a UNIX command line interpreter
3. Simple shell 0.1 + Handle command lines with arguments
4. Simple shell 0.2 + Handle the PATH + fork must not be called if the command doesn’t exist 
5. Simple shell 0.3 + Implement the exit built-in, that exits the shell + Usage: exit You don’t have to handle any argument to the built-in exit
6. Simple shell 0.4 + Implement the env built-in, that prints the current environment
7. Write your own getline function, Use a buffer to read many chars at once and call the least possible the read system call
8. You are not allowed to use strtok
9. handle arguments for the built-in exit, Usage: exit status, where status is an integer used to exit the shell
10. Implement the setenv and unsetenv builtin commands
11. Implement the builtin command cd
12. Handle the commands separator ;
13. Handle the && and || shell logical operators
14. Implement the alias builtin command, Usage: alias [name[='value'] ...]
15. Handle variables replacement Handle the $? variable Handle the $$ variable
Handle comments (#)
Usage: simple_shell [filename] Your shell can take a file as a command line argument The file contains all the commands that your shell should run before exiting The file should contain one command per line In this mode, the shell should not print a prompt and should not read from stdin

Author's
Okelo Maxwel and Sharline Mwende