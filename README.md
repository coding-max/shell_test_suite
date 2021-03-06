# Simple Shell Test Suite

![markdown poster by Jorge Tuset](./assets/CHECKER.jpg)

> Please, in order to avoid any conflicts **DO NOT edit** any files from this repository neither on Github nor on your local repository, with the exception of "AUTHORS".  
> If you wish to modify the list of test cases, run the script and follow the instructions, the list will be automatically synchronized.  
> **You must never do a manual push** in order to avoid uploading run files or test results.  

## How to use the tool

This test suite is based on a shell script that manages the test cases for all versions of the simple shell.  

### Prepare the environment

The first thing to do is clone the repository with the command `git clone https://github.com/coding-max/shell_test_suite.git`.  
Once cloned, the simple shell executable must be added to it (the `hsh` file generated by `gcc -Wall -Werror -Wextra -pedantic * .c -o hsh`).  

### Run the tool

To run the test suite, use the command: (`./test_suite`). Once inside the test suite, you need to enter your holberton ID (so as to recognize who modified the list at the time of pushing changes).  
This tool has a guided menu for each of these steps.  

This tool allow you to:  

- Run test cases for a specific version of the simple shell.
- List the current test cases for a specific version (at the end it will allow you to select a case to be deleted if necessary).  
- Add new test cases for a specific version.

### Sync

The shell script synchronizes the list of cases (together with its github version) every time a new test is run or the list is edited.  
Every time you modify a list of cases, the new resulting list is updated on github so it is important to be connected to the internet.  

## Additional information

After adding test cases, you must add yourself as a contributor. For this you must edit the "AUTHORS" file (do it from github, not in your local repository so as to avoid any conflicts).  
The correct way to add your information to the file is as follows: `Name <email>`.  