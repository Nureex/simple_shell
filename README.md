![Shell Logo](https://github.com/Nureex/Files/blob/master/Photos/Shell.jpg)

# simple_shell project repository

This repository contains the files for ALX's **simple_shell**. It can be compiled using GCC and will execute a simple shell that can be used for some basic tasks and programs most commonly found in the /bin/ folder.

# Pre-requisites

### Authorized functions and macros:
- access (man 2 access)
- chdir (man 2 chdir)
- close (man 2 close)
- closedir (man 3 closedir)
- execve (man 2 execve)
- exit (man 3 exit)
- _exit (man 2 _exit)
- fflush (man 3 fflush)
- fork (man 2 fork)
- free (man 3 free)
- getcwd (man 3 getcwd)
- getline (man 3 getline)
- isatty (man 3 isatty)
- kill (man 2 kill)
- malloc (man 3 malloc)
- open (man 2 open)
- opendir (man 3 opendir)
- perror (man 3 perror)
- read (man 2 read)
- readdir (man 3 readdir)
- signal (man 2 signal)
- stat (__xstat) (man 2 stat)
- lstat (__lxstat) (man 2 lstat)
- fstat (__fxstat) (man 2 fstat)
- strtok (man 3 strtok)
- wait (man 2 wait)
- waitpid (man 2 waitpid)
- wait3 (man 2 wait3)
- wait4 (man 2 wait4)
- write (man 2 write)


## Function Prototypes:

### Brief description of functions contained in project:

- **_strcmpdir** :  compares strings to find dir.
- **find_command** :  finds command to execute in path routes.
- **charput** :  writes the character like putchar.
- **place** :  similar to puts in C.
- **_strlen** :  string length.
- **str_concat** :  concatenate strings.
- **lookforslash** :  identify if first char is a '/'.
- **compareExit** :  checks if user typed exit.
- **compareEnv** :  checks if user typed env.
- **execute_proc** :  receives command and args from getline to be executed.
- **identify_string** :  returns pointer with folder address.
- **prompt** :  infinite loop with fork to keep prompt going.
- **controlC**: avoid program closing when pressing ctrl + c.
- **main**: initialize program.


**_This code was created by Nura Aliyu and Ismaila Ibrahim!_**

