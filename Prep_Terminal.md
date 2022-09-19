[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Prep-work Practice in the Terminal

## Notes Summary

### Basic Navigation

PWD - print working directory

ls - list files at location. (ls[options][locations])

cd - change directories

Absolute path - a location in relation to the root directory.

Relative path - la location in relation to where we currently are in the system.

tilde(~) - shortcut for home directory.

dot(.) - reference to the current directory.

dotdot(..) - reference to parent directory.

### More about files

In Linux, under the hood, everything is a file. The system determines the file type by reading the file, not the file extension. We can use (file[path]) to determine the file type if needed. Linus is case sensitive, file extensions too. Spaces in file and directories are valid but not reccomended as they can cause confusion. Hidden files and directories start with a dot(.). Use (ls -a) to list all hidden files and directories.

### Manual Pages

(man[command]) - to open manual pages about the command. Hint: press 'q' to quit the manual.

(man -k [search term]) - search keyword term on the manual pages. To search within current manual page use (/[term]) and hit enter. Use 'n' key to cycle through the search results.

### File Manipulation

(mkdir[options][name]) - will make a new directory with the name provided. Options (-p) make parent folders as neccessary. (-v) will have mkdir tell us what it is doing when creating the file/directory.

(rmdir[options][name]) - remove a directory. Notes : A directory must be empty before it can be removed. Also -p/-v options work with rmdir as well.

(touch[options][file name]) - create a empty file.

(cp[options][source][destination]) - copy a file or directory from source to destination.

(mv[options][source][destination]) - move a file or directory. Hint: can be used to rename if source and destination are the same.

(rm[options][file]) - remove a file.

(rm -r [directory]) - remove a non-empty directory.

Last but not least. THE COMMAND LINE HAS NO UNDO!

## Things I want to know more about

How to properly utilize the terminal in integrate/expediate my coding. I understand some basics but I prefer GUI's. 

-----