# PowerShell and Terminal Cheat Sheet

PowerShell and zsh are examples of a type of program called a "shell".
A shell is a program that the user can use to interact with the operating system
in some way, most commonly through typing lines of commands with the keyboard.
(Another name for this type of interaction is "command line interface".)

This is a quick list of some useful commands.

Note: "Directory" and "folder" are the same thing.

## Commands that work mostly the same for PowerShell and Mac Terminal (zsh)

- `cd` - Change Directory.
- `ls` - List. Shows the files and subdirectories of the current working directory.
- `rm` - Remove. Type a space-separated list of filenames after this command, and all the named files will be deleted.
- `rmdir` - Remove Directory. Just like `rm`, but for directories.
- `mkdir` - Make Directory. Type a name for a new directory, and a directory with that name will be created as a subdirectory of the current working directory.

## Gradle commands

We are using Gradle for building Java projects. Gradle has a lot of command-line `tasks`, but the most commonly used ones are:

- `gradle build` - Build the project and run any unit tests
- `gradle run` - Run this project.
- `gradle simulateJava` - For FRC projects, run the robot simulator

