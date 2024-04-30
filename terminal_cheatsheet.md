# Terminal Cheatsheet 💻

The following markdown document contains a handy **Terminal Cheatsheet** with useful terminal commands for a quick reference for budding programmers and sys admins. Please feel free to suggest any potential improvements or commands that you want to see added in the issues tab.

## Basic Commands 👾

### Navigation

* `ls` - Probably one of the first commands you learn in any commandline tutorial. `ls` allows you to list the current directory's contents, including files and other directories.
* `cd` - Short for _change directory_, this command allows you to move between directories and navigate your way through your computers file system.
* `pwd` - Print Working Directory, or pwd for short, allows you to see the current directories path.

### File and Directory Management

* `mkdir` - Short for _make directory_, this command allows you to create a directory within the one you are currently operating within.
* `cp` - This command allows you to copy a file or directory.
* `mv` - The move command allows you to move files and directories. But not only that, with this command you can move a file or directory to the sameplace, but this time giving it a new name. Thus renaming your file/directory!
* `rm` - Removes files and directories, without warning (**Careful with this one!**).
* `rmdir` - Like `rm` but specifically for directories.
* `touch` - Allows you to create empty files.

## Flags 🏳️

Flags are used to further improve the functionality for your terminal commands. Allowing you to gain more information or extend the functionality of your command to perform specific actions.

| Flag | Use |
|------|------|
| - l  | Creates a detailed list when used along side the `ls` command |
| - r  | Recursive |
| - f  | Force an operation |
| - a  | Essentially means **all**, can be used with `ls` to list all files and directories, including hidden ones |
| - h  | Help command for...commands |
| - y  | Answer yes to all prompts |

## Git Commands 

Below are a few useful **Git** commands!

* `git init` - Initialises a git repo.
* `git add -A` - Stages new and modified files within a git repo.
* `git commit -m "MESSAGE HERE"` - Commits staged files, complete with a message for the commit.
* `git push` - Pushes the commited files to the git repo on GitHub!