## Task 0: Where am I?
This task involves creating a script that prints the absolute path name of the current working directory.

## Task 1: What's in there?
In this task, a script is provided to display the contents list of the current directory.

## Task 2: There is no place like home
The objective of this task is to create a script that changes the working directory to the user's home directory.

## Task 3: The long format
For this task, a script is created to display the current directory contents in a long format, including details like file permissions, owner, size, and modification time.

## Task 4: Hidden files
The goal of this task is to modify the script from Task 3 to include hidden files (those starting with `.`) in the long format directory listing.

## Task 5: I love numbers
In this task, the script from Task 4 is further modified to display user and group IDs numerically instead of using names.

## Task 6: Welcome
Create a script that creates a directory named `my_first_directory` in the `/tmp/` directory.

## Task 7: Betty in my first directory
Move the file `betty` from `/tmp/` to `/tmp/my_first_directory`.

## Task 8: Bye bye Betty
Delete the file `betty` from `/tmp/my_first_directory`.

## Task 9: Bye bye My first directory
Delete the directory `my_first_directory` that is in the `/tmp` directory.

## Task 10: Back to the future
Write a script that changes the working directory to the previous one.

## Task 11: Lists
Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory, the parent of the working directory, and the `/boot` directory (in this order), in long format.

## Task 12: File type
Write a script that prints the type of the file named `iamafile`. The file `iamafile` will be in the `/tmp` directory when we run your script.

## Task 13: We are symbols, and inhabit symbols
Create a symbolic link to `/bin/ls`, named `__ls__`, in the current working directory.

## Task 14: Copy HTML files
Create a script that copies all the HTML files from the current working directory to the parent of the working directory. Only copy files that do not exist in the parent directory or are newer than the versions in the parent directory.

## Task 15: Let's move
Create a script that moves all files beginning with an uppercase letter to the directory `/tmp/u`.

## Task 16: Clean Emacs
Create a script that deletes all files in the current working directory that end with the character `~`.

## Task 17: Tree
Create a script that creates the directories `welcome/`, `welcome/to/`, and `welcome/to/school` in the current directory. The script should only use two spaces (and lines) in its code.

## Task 18: Life is a series of commas, not periods
Write a command that lists all the files and directories of the current directory, separated by commas (,). Directory names should end with a slash (/), and files/directories starting with a dot (.) should be listed. The listing should be alphabetically ordered, except for the directories `.` and `..`, which should be listed at the beginning. Only digits and letters are used to sort, with digits coming first.

## Task 19: File type: School
Create a magic file `school.mgc` that can be used with the `file` command to detect School data files. School data files always contain the string "SCHOOL" at offset 0.
