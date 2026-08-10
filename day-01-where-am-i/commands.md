# Day 01: Where Am I? Basic Orientation

## Commands of the day

**1. pwd**

`pwd` stands for **Print Working Directory**

This command is used to print the current working directory. It tells you the location you're currently in the file system.

Imagine a situation where you're working in a linux server and you've `cd` into various directories and lost track of where you're. It will be very much helpful to print your working directory by typing the command `pwd`.

**2. ls**

This command lists the contents of a directory. If no directory is passed, it list the content of the current directory.

`ls [options] [directory]`

**3. ls -l**

This command is used to list the contents of a directory and show the details of each content. The details include;

- File type
- Owner
- Group
- Size
- Permission

**4. ls -a**

This command is used to list all files including hidden files. Hidden files are files whose name starts with a dot. It can either be a file or a directory.

It can as well be combined with `l` to give `ls -al`.

**5. ls -la**

This command list all files in long format including the hidden files.

**6. ls -lh**

This command list all the files in long format and format the file sizes to make it human-readable (e.g. **4.0k**, **1.2M**)

**7. cd**

This command gives you wings to jump to any directory by providing the absolute path.

`cd /var/www/my-app`

**8. cd ..**

This command moves you up by one level to the parent directory of where you currently are.

**9. cd ~**

This command takes you to your home directory.

It can also be combined with subpaths. e.g. `cd ~/projects/api-server`

**10. cd -**

This command takes you back to the previous directory you were in before your last cd command.
