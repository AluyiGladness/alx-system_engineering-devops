0-current_working directory -This is a script that prints the absolute path name of the current working directory.

1-listit -This is a file that displays the contents list of your current directory.

2-bring_me_home - This is a script that changes the working directory to the user’s home directory. You are not allowed to use any shell variables

3-listfiles - Display current directory contents in a long format

4-listmorefiles - Display current directory contents, including hidden files (starting with .). This is done using the long format.

5-listfilesdigitonly - Display current directory contents. Long format with user and group IDs displayed numerically And hidden files (starting with .)

6-firstdirectory - Create a script that creates a directory named holberton in the /tmp/ directory.

7-movethatfile - This is a file that moves an arbitrary file betty from /tmp/ to /tmp/holberton.

8-firstdelete - Delete the file betty. The file betty is in /tmp/holberton

9-firstdirdeletion - Delete the directory holberton that is in the /tmp directory.

10-back - This is a script that changes the working directory to the previous one.

11-lists - This is a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

12-file_type - This is a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

13-symbolic_link - Create a symbolic link to /bin/ls, named ls. The symbolic link should be created in the current working directory.

14-copy_html - Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. You can consider that all HTML files have the extension .html

15-lets_move - Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u. You can assume that the directory /tmp/u will exist when we will run your script

16-clean_emacs - Create a script that deletes all files in the current working directory that end with the character ~.

17-tree - Create a script that creates the directories welcome/, welcome/to/ and welcome/to/holberton in the current directory. You are only allowed to use two spaces in your script, not more.

18-commas - Write a command that lists all the files and directories of the current directory, separated by commas (,).

Directory names should end with a slash (/) Files and directories starting with a dot (.) should be listed The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning Only digits and letters are used to sort; Digits should come first You can assume that all the files we will test with will have at least one letter or one digit The listing should end with a new line.

holberton.mgc - Create a magic file holberton.mgc that can be used with the command file to detect Holberton data files. Holberton data files always contain the string HOLBERTON at offset 0.
