Project:
AirBnB clone Console

Description:
This is the first part of the AirBnB clone project, the interface of the application is like the Bash shell except that this one has a limited number of commands that are defined for the purpose of using it in the AirBnB website. 
This command line interpreter serves as the frontend of the web app where users can interact with the backend.

Some commands available in the console:
show
create
update
destroy
count


How to start it: 
You will have to clone the repo from Github which will contain the program and all its dependencies. 
After the clonning run "./console.py" in your terminal to start it

How to use it:
It works in two modes- Interactive and Non-interactive.

Interactive mode- The console will display a prompt (hbnb) meaning the user can write and execute a command. After the command is run, the prompt will appear for a new command. This goes on endlessly as long as the user does not exit the program.
Example:
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$

Non-interactive mode- The console will need to run with a command input piped into its execution so that the command is executed immediately the console starts. no prompt appears in this mode, plus no other input is expected from the user.
Example:
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
