# System Engineering Development & Operations
                              PROJECTS

> System Engineering & DevOps - Bash
## 0x00. Shell, basics
### Learning Objectives: [DevOps, Shell, Bash]
- What does RTFM mean?
- What is a Shebang
#### What is the Shell
- What is the shell
- What is the difference between a terminal and a shell
- What is the shell prompt
- How to use the history (the basics)
#### Navigation
- What do the commands or built-ins cd, pwd, ls do
- How to navigate the filesystem
- What are the . and .. directories
- What is the working directory, how to print it and how to change it
- What is the root directory
- What is the home directory, and how to go there
- What is the difference between the root directory and the home directory of the user root
- What are the characteristics of hidden files and how to list them
- What does the command cd - do
#### Looking Around
- What do the commands ls, less, file do
- How do you use options and arguments with commands
- Understand the ls long format and how to display it
- A Guided Tour
- What does the ln command do
- What do you find in the most common/important directories
- What is a symbolic link
- What is a hard link
- What is the difference between a hard link and a symbolic link
#### Manipulating Files
- What do the commands cp, mv, rm, mkdir do
- What are wildcards and how do they work
- How to use wildcards
#### Working with Commands
- What do type, which, help, man commands do
- What are the different kinds of commands
- What is an alias
- When do you use the command help instead of man
#### Reading Man Pages
- How to read a man page
- What are man page sections
- What are the section numbers for User commands, System calls and Library functions
#### Keyboard Shortcuts for Bash
- Common shortcuts for Bash
#### LTS
- What does LTS mean?


## 0x01. Shell, permissions
### Learning Objectives: [DevOps, Shell, Bash]
#### Permissions
- What do the commands chmod, sudo, su, chown, chgrp do
- Linux file permissions
- How to represent each of the three sets of permissions (owner, group, and other) as a single digit
- How to change permissions, owner and group of a file
- Why can’t a normal user chown a file
- How to run a command with root privileges
- How to change user ID or become superuser
#### Other Man Pages
- How to create a user
- How to create a group
- How to print real and effective user and group IDs
- How to print the groups a user is in
- How to print the effective userid


## 0x02. Shell, I/O Redirections and filters
### Learning Objectives: [DevOps, Shell, Bash]
#### Shell, I/O Redirection
- What do the commands head, tail, find, wc, sort, uniq, grep, tr do
- How to redirect standard output to a file
- How to get standard input from a file instead of the keyboard
- How to send the output from one program to the input of another program
- How to combine commands and filters with redirections
#### Special Characters
- What are special characters
- Understand what do the white spaces, single quotes, double quotes, backslash, comment, pipe, command separator, tilde and how and when to use them
#### Other Man Pages
- How to display a line of text
- How to concatenate files and print on the standard output
- How to reverse a string
- How to remove sections from each line of files
- What is the /etc/passwd file and what is its format
- What is the /etc/shadow file and what is its format


## 0x03. Shell, init files, variables and expansions
### Learning Objectives: [DevOps, Shell, Bash]
- What happens when you type $ ls -l *.txt
#### Shell Initialization Files
- What are the /etc/profile file and the /etc/profile.d directory
- What is the ~/.bashrc file
#### Variables
- What is the difference between a local and a global variable
- What is a reserved variable
- How to create, update and delete shell variables
- What are the roles of the following reserved variables: HOME, PATH, PS1
- What are special parameters
- What is the special parameter $??
#### Expansions
- What is expansion and how to use them
- What is the difference between single and double quotes and how to use them properly
- How to do command substitution with $() and backticks
#### Shell Arithmetic
- How to perform arithmetic operations with the shell
### The alias Command
- How to create an alias
- How to list aliases
- How to temporarily disable an alias
#### Other help pages
- How to execute commands from a file in the current shell


## 0x04. Loops, conditions and parsing
### Learning Objectives: [DevOps, Shell, Bash, Scripting]
- How to create SSH keys
- What is the advantage of using #!/usr/bin/env bash over #!/bin/bash
- How to use while, until and for loops
- How to use if, else, elif and case condition statements
- How to use the cut command
- What are files and other comparison operators, and how to use them


## 0x05. Processes and signals
### Learning Objectives: [DevOps, Shell, Bash, Syscall, Scripting]
- What is a PID
- What is a process
- How to find a process’ PID
- How to kill a process
- What is a signal
- What are the 2 signals that cannot be ignored


                    System Engineering & DevOps - Scripting
## 0x06. Regular expression
### Learning Objectives: [Regex, DevOps]
> Concepts
For this project, we expect you to look at this concept:
- Regular Expression: https://intranet.alxswe.com/concepts/29

> Background Context
For this project, you have to build your regular expression using Oniguruma, a regular expression library that which is used by Ruby by default. Note that other regular expression libraries sometimes have different properties.


                     System Engineering & DevOps - Networking
## 0x07. Networking basics #0
### Learning Objectives: DevOps, Network
#### OSI Model
- What it is
- How many layers it has
- How it is organized
#### What is a LAN
- Typical usage
- Typical geographical size
#### What is a WAN
- Typical usage
- Typical geographical size
#### What is the Internet
- What is an IP address
- What are the 2 types of IP address
- What is localhost
- What is a subnet
- Why IPv6 was created
#### TCP/UDP
- What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)
- What is the main difference between TCP and UDP
- What is a port
- Memorize SSH, HTTP and HTTPS port numbers
- What tool/protocol is often used to check if a device is connected to a network


## 0x08. Networking basics #1
### Learning Objectives: [DevOps, Network, SysAdmin]
- What is localhost/127.0.0.1
- What is 0.0.0.0
- What is /etc/hosts
- How to display your machine’s active network interfaces

## 0x09. Web infrastructure design
### Learning Objectives: [DevOps, SysAdmin, web infrastructure]
- You must be able to draw a diagram covering the web stack you built with the sysadmin/devops track projects
- You must be able to explain what each component is doing
- You must be able to explain system redundancy
- Know all the mentioned acronyms: LAMP, SPOF, QPS

