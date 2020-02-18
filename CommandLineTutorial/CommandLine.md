# Welcome to the VFOSS command line tutorial!
In this lesson, we will teach you all the skills you will need to know 
and how to find our information about the things you need.

# Intro to command line
## Basics
To open terminal:

    Linux: Ctrl+Alt+T, or find it in applications
    Windows: open git bash
    Mac: find it in applications

most commands are in the format of

    command [options] [args] 

Options are usually preceded by - or --, for example:

    vim -h
    vim --help

Arguments usually just follows the command, for example:

    Linux: telnet towel.blinkenlights.nl
    Windows: telnet towel.blinkenlights.nl
    Mac Sierra+: nc towel.blinkenlights.nl 23
    Mac Sierra-: telnet towel.blinkenlights.nl

## File System
File directories consists of folders and files seperated by 
    
    /

for example:
    
    ~/Desktop/folder/file

Below are some special directory and file types:

    /           represents root diretory
    ~           represents home/user directory
    .           represents the current directory  
    ..          represents the parent directory  
    .name       represents hidden files or directories
    file.ext    represents the file with a specific extention

Below are some simple terminal commands to navigate the file system:

    ls          list contents of a directory (folder)  
    cd          change directory  
    mkdir       create a directory  
    rm          remove a file
    rm -r       remove a folder.  
    'Tab'       auto-complete path
    'Up Arrow'  last entered command

## Getting Help
Most commands have a -h or --help option, for example:

    vim -h
    vim --help

For more detailed information on command, most commands also has a manual page, for example:

    man [command]

To search manual pages for a term:

    man -k [keyword]

## Sudo
The sudo command before another line of command runs a command as root or admin user

    sudo [command]

## Package Management
Most Linux based operating systems, such as Ubuntu, come with an application manager much like how MacOS has 'App Store' and Windows has 'Microsoft Store'. 

Some basic instructions to navigate the application manager are as follows:

    sudo apt update  
    sudo apt upgrade  
    sudo apt install [package]  
    sudo apt remove [package]  
    apt-cache search [keyword] 

## Variables
Set variable: var=value  
Use value: $var  

Environment variables get passed to child processes.  
Create an environment variable: export var=value  
Run command with different environment: env var=value command  
Print all environment variables: env or printenv  
Print specific variable: printenv var

## For futher exploration...
find, grep  
top, kill  
touch, echo, awk, less, cat, sed, |  
vim
Up arrow key: previous command
