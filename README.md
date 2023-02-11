PROJECT DESCRIPTION:
This is a team project for a complete web application: integrating database storage, HTML/CSS templating, API, front-end, etc.

The project is part of the ALX School Software Engineering program which focuses on the first step towards building a full web application: the AirBnB clone.

This first step consists of:

1. creating a custom command-line interface for data management.

2. creating the base classes for the storage of this data.



COMMAND LINE INTERPRETER:
This is a shell-like console but for specific usage.

How To Start: ./console.py

Create An Object: (hbnb) create <class> 

Show an object: (hbnb) show <class> <id> or (hbnb) <class>.show(<id>) 

Show 'help' for a command: (hbnb) help <command> 

Destroy An Object: (hbnb) destroy <class> <id>

Quit Console: (hbnb) quit


EXAMPLES:

Interactive Mode:
$ ./console.py

(hbnb) help



Documented commands (type help <topic>):

========================================

EOF  help  quit



(hbnb)

(hbnb)

(hbnb) quit

$



Non Interactive Mode:
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


