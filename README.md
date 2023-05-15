# 0x00. AirBnB clone - The console #

This project is the first step towards building a full web application: the AirBnB clone.


## Table of Contents ##

_Objectives_

_Requirements_

_Installation and execution_

_Console commands_

_Tests_

_Development environment_

_Authors_

## Objectives ##

- How to create a Python package
- How to create a command interpreter in Python using the cmd module
- What is Unit testing and how to implement it in a large project
- How to serialize and deserialize a Class
- How to write and read a JSON file
- How to manage datetime
- What is an UUID
- What is _*args_ and how to use it
- What is **kwargs and how to use it
- How to handle named arguments in a function

# Requirements #
All files were interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)


# Installation and execution #

* Clone the repository
 https://github.com/StephOkok/AirBnB_clone.git
* Move in to the directory
$ cd AirBnB_clone
* Execute the console file
/AirBnB_clone$ ./console.py

# Console commands #

_The commands available for this command interpreter are:
| Command | Description |
| --- | --- |
| Create | Creates a new instance of the class passed by argument. |
| Show | Prints the string representation of an instance. |
| Destroy | Deletes an instance that was already created. |
| All 	| Prints string representation of all instances or of all instances of a specified class.|
| Update | Updates an instance attribute if exists otherwise create it. |
| Help | Show all commands or display information about a specific command. |
| Quit | Exit the console. |                                      |
| EOF | Exit the console. |         
| Create | destroy and update commands save changes into a JSON file. |
| Create | create <class_name> |
| Show 	| show <class_name> <object_id> ; <class_name>.show(<object_id>)() |
| Destroy | destroy <class_name> <object_id ; <class_name>.destroy(<object_id>)() |
| All | all <class_name> ; <class_name>.all() |
| Update | update <class_name> <object_id> <attribute name> “<attribute value>” ; <class name>.update(<object_id>, <attribute name>, <attribute value>) ; <class name>.update(<object_id>, <dictionary representation>) |
| Help | help ; help <command_name> |
| Quit | quit |
| EOF | EOF ; (ctrl + d) |

## Storage ##

All the classes are handled by the Storage engine in the FileStorage Class.  
  
## Testing - Unittest modules ##
All the test are defined in the tests folder.

## Documentation ##
Modules:
python3 -c 'print(__import__("my_module").__doc__)'

## Classes: ##
python3 -c 'print(__import__("my_module").MyClass.__doc__)'

Functions (inside and outside a class):
python3 -c 'print(__import__("my_module").my_function.__doc__)'
and
python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'

Python Unit Tests

- Unittest module
- File extension .py
- Files and folders start with test_
Organization:for models/base.py, unit tests in: tests/test_models/test_base.py

Execution command: python3 -m unittest discover tests
or: python3 -m unittest tests/test_models/test_base.py
  
# Development Environment #
  Style guidelines:
    pycodestyle (version 2.7.*)
    PEP8
# Author #
- Sebastian Kimanzi 
- Github <seb-art> 
