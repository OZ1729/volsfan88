# Command Line

### Link to common command line commands
- https://www.codecademy.com/articles/command-line-commands
## Navigation
ls (List) - Lists contents of specified directory. Defaults to current directory if one is not specified
> $ ls Desktop  
resume.pdf  
photo.png
- [ls -a] lists all contents, including hidden files
- [-l] lists all contents in long format
- [-t] lists all contents by time they were last modified


pwd(Print Working Directory) - displays the filepath to the current working directory from the root
>$ pwd  
/Users/sonny/Downloads


mkdir(Make Directory) - Creates a new directory. Can be given file path or defaults into the current working directory
> $ mkdir new-directory  
$ ls  
old-directory    new-directory


cd(Change Directory) - Changes directory with flexible arguments. Can be full filepaths, names of children directories, or can use .. to move back up to parent directory
> $ cd some-directory  
$ cd ..

touch - creates a new file in the current directory, must provide name for the file
> $ touch grocery-list.txt

cp(Copy) - basic structure is
> cp 'source' 'destination'
- can copy files or directories
>$ cp file1 file1\_copy  
$ cp file1 file2 destination\_folder

Helper Commands
> clear - clears terminal
> tab - autocompletes line
> up arrow and down arrow cycles through commands

## Command Options
These can be used to modify the behavior of shell commands. There are many but are represented by a dash followed by a letter. -a for example

### 'Deathstar' command
- rm -rf *.* - Deletes all folders and files in a directory