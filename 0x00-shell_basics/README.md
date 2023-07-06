0-current_working_directory - Prints the absolute path name of the working directory
1-listit - Displays the contents list of the current directory
2-bring_me_home - Changes the working directory to the user's home directory
3-listfiles - Diplays current directory contents in a long format
4-listmorefiles - Displays current directory contents, including hidden files (starting with .) using the long format.
5-listfilesdigitonly - Displays current directory contents, including hidden files (starting with .) using the long format with user and group IDs displayed numerically.
6-firstdirectory - Creates a directory named "my_first_directory" in the "/tmp/" directory.
7-movethatfile - Moves the file "betty" from "/tmp/" to "/tmp/my_first_directory".
8-firstdelete - Deletes the file "betty" in "/tmp/my_first_directory".
9-firstdirdeletion - Delete the directory "my_first_directory" that is in the "/tmp" directory.
10-back - Changes the working directory to the previous directory.
11-lists - Lists all files (including ones that start with .) in the current directory and the parent fo the working directory and the '/boot' directory (in that order), in long format.
12-file_type - Prints the type of the filed named 'iamafile' in the 'tmp' directory.
13-symbolic_link - Creates a symbolic link to '/bin/ls', named '__ls__'.
14-copy_html - Copies all the HTML from the current working directory to the parent of the working directory, but only copies the files that did not exist in the parent of the working directory or are newer than the versions in teh parent of the working directory.

### Advanced tasks
100-lets_move - Moves all files beginning with an uppercase letter to the directory "/tmp/u".
101-clean_emacs - Deletes all files in the current working directory that end with the character '~'.
102-tree - Creates the directories 'welcome/', 'welcome/to/' and 'welcome/to/school' in the current directory.
103-commas - Lists all the files & directory of the current directory, separated while using the following constraints: directory names should end with a slash(/), files & directories starting with dot(.) should be listed, the listing should be alpha ordere except for the directories . and .. which should be listed at the very beginning, only digits and letter are used to sort - digits should come first, and the listing should end with a new line.
school.mgc A magic file that can be used with the command 'file' to detect 'School' data files. 'School' data files alwasys contain the string 'SCHOOL' at offset 0.
