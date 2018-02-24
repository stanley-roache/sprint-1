command line is a tool used to interact with a computer or server (remote computer you are connected to). With it you can navigate through the storage system of the computer, create, delete and edit files (objects in the computer system that contain information) and directories (folders in the computer that hold files and other directories) and more generally tell the system what to do (commands). Every time you press enter, what you have typed in is intepreted and acted out by the system.

Command line use involves only reading and entering text into a window.

Here are some Command Line commands.

pwd:

'print working directory', this tells you where in the computer's file system the terminal is currently operating from

cd:

change directory, this command allows the user to move to another directory

ls:

list the contents of the current directory

rm:

remove (delete) a file or directory

mv:

move a file or directory from one location to another

cp:

copy a file or directory from one location to another

mkdir:

create a directory

cat:

used to print out the contents of a file to the terminal screen

man:

show the terminal manual for a given command, this is useful to learn more about how to use an unfamiliar command

vi:

this opens a file in the command line in a text editor

cut:

This is a cool command that treats the file as a grid, rows are seperated by return characters, columns are separated by a delimiter that defaults to TAB. It outputs the same structure but only the specified columns
EG. cut -f 1,3 -d 'DELIMITER' input_file
this will print out the first and third fields of each line that are separated by 'DELIMITER' 

nl: 

Go through a file and number the lines