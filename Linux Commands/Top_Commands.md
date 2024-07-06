#### ###################### man ###################################################

The man command in a terminal is used to display the manual pages for various commands

-f: Displays a short description of the command or topic, without the detailed manual page.

#### ###################### ls ###################################################

When using the ls command in a terminal, there are several flags that can be useful for different purposes. Here are some commonly used flags with ls:

-l: Displays the long format listing, providing detailed information about files and directories, including permissions, owner, size, and modification date.

-a: Shows all files, including hidden files and directories (those starting with a dot).

-h: Prints file sizes in a human-readable format, such as "K" for kilobytes, "M" for megabytes, etc.

-S: Sorts files by size, with the largest file appearing first.

-t: Sorts files by modification time, with the most recently modified file appearing first.

-r: Reverses the order of the sorting. Used in combination with -S or -t, it will display the smallest or oldest files first.

-R: Recursively lists files and directories, showing the contents of subdirectories as well.

These flags can be combined to suit your specific needs. For example, ls -lha will list all files (including hidden ones) in a long format with human-readable file sizes.


#### ###################### cp ###################################################

The cp command in a terminal is used to copy files and directories from one location to another. Here are some commonly used flags with the cp command:

-r or -R: Recursively copies directories and their contents. This flag is necessary when copying directories.

-i: Prompts for confirmation before overwriting an existing file.

-v: Enables verbose output, displaying the name of each file as it is copied.


-p: Preserves the original file attributes, such as permissions, timestamps, and ownership.


#### ###################### mv ###################################################

The mv command in a terminal is used to move or rename files and directories. It can be used to move files/directories from one location to another or to simply rename them. Here are some commonly used flags with the mv command:

-i: Prompts for confirmation before overwriting an existing file.

-v: Enables verbose output, displaying the name of each file as it is moved or renamed.


#### ###################### rm ###################################################
The rm command in a terminal is used to remove files and directories. It allows you to delete files and directories permanently. Here are some commonly used flags with the rm command:

-i: Prompts for confirmation before deleting each file.

-r or -R: Recursively removes directories and their contents.

-f: Forces the deletion without prompting for confirmation.

-v: Enables verbose output, displaying the name of each file as it is deleted.


###################### df ###################################################

The df command in a terminal is used to display information about file system disk space usage.
-h: Displays the disk space usage in a human-readable format, using units like "K" (kilobytes), "M" (megabytes), "G" (gigabytes), etc.
-T: Displays the file system type along with disk space usage.
-a: Shows information about all file systems, including those with zero blocks used.

###################### cat ###################################################
The cat command in a terminal is used to display the contents of files in the terminal window

-n: Displays line numbers along with the file contents.

###################### tail ###################################################
The tail command in a terminal is used to display the last part of a file or output

-n N: Specifies the number of lines to display from the end of the file. For example, -n 10 displays the last 10 lines. By default, tail displays the last 10 lines if the -n option is not used.
-f: Follows the file and displays appended data as it is written to the file. This is useful for monitoring log files or real-time changes. To exit the tail -f command, you can press Ctrl + C.

