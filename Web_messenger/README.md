# Welcome to Project: Web Messenger!

First step is to write a command interpreter to manage objects.
This command interpreter will be used for other projects such as: HTML/CSS templating, database storage, API, front-end integration…

The command interpreter works exactly like the shell but limited to a specific use-case
In this project case, it will be able to manage the objects of our project:
1. Create a new object (ex: a new User or a new Place)
2. Retrieve an object from a file, a database etc…
3. Do operations on objects (count, compute stats, etc…)
4. Update attributes of an object
5. Destroy an object

All together, the command interpreter will help to:
1. Put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
2. Create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
3. Create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
4. Create the first abstracted storage engine of the project: File storage.
5. Create all unittests to validate all our classes and storage engine

# STARTING THE CONSOLE:
=====================
To start the console, use: <./console.py> or <python console.py> without the angle brackets

USAGE:
======
Once the console is running, enter commands and press enter
Example: Entering <hello> without the brackets in the console will call the do_hello() method and pass the remaining words on that line to it as parameters

To exit the console, use: ctrl+d or type <quit> without the angle brackets
Other details can be found using the <help> command or <?> wildcard
