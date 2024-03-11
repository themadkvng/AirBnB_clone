# AirBnB Clone Project

Welcome to the AirBnB clone project! This project aims to create a command-line interpreter to manage AirBnB objects, serving as a foundational step towards building a full web application.

## Description of the Command Interpreter

The command interpreter allows users to perform various operations on AirBnB objects:

- Create new objects (e.g., User, Place)
- Retrieve objects from storage
- Perform operations on objects (e.g., count, compute stats)
- Update attributes of an object
- Delete an object

## How to Start It

To start the command interpreter, run the `console.py` script:

```
$ ./console.py
```

## How to Use It

Once the command interpreter is running, you can enter commands to interact with AirBnB objects. Here are some basic commands:

- `create <class>`: Create a new instance of the specified class.
- `show <class> <id>`: Display the details of the object with the given ID.
- `update <class> <id> <attribute> <value>`: Update the specified attribute of the object.
- `destroy <class> <id>`: Delete the object with the given ID.
- `all <class>`: Display all instances of the specified class.
- `quit`: Exit the command interpreter.

For detailed information on available commands and their usage, use the `help` command within the interpreter.

## Examples

```
$ ./console.py
(hbnb) create User
f8bb12a2-1395-4e21-9f63-4a9e2b4d3a43
(hbnb) show User f8bb12a2-1395-4e21-9f63-4a9e2b4d3a43
[User] (f8bb12a2-1395-4e21-9f63-4a9e2b4d3a43) {'id': 'f8bb12a2-1395-4e21-9f63-4a9e2b4d3a43', 'created_at': '2024-03-11T12:00:00', 'updated_at': '2024-03-11T12:00:00'}
(hbnb) update User f8bb12a2-1395-4e21-9f63-4a9e2b4d3a43 name John
(hbnb) show User f8bb12a2-1395-4e21-9f63-4a9e2b4d3a43
[User] (f8bb12a2-1395-4e21-9f63-4a9e2b4d3a43) {'id': 'f8bb12a2-1395-4e21-9f63-4a9e2b4d3a43', 'created_at': '2024-03-11T12:00:00', 'updated_at': '2024-03-11T12:01:00', 'name': 'John'}
(hbnb) quit
$
```

This README serves as a guide to understand and use the AirBnB command interpreter. For further details on the project structure, learning objectives, and requirements, please refer to the project guidelines and documentation.
