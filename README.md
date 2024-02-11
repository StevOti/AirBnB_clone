Hbnb - Airbnb Clone
Project Description
Hbnb is a simplified Airbnb clone project that aims to replicate some of the basic functionalities of the popular vacation rental platform, Airbnb. This project is designed to be a learning exercise and provides a command-line interface (CLI) for users to interact with the system.

Command Interpreter Description
The command interpreter is a text-based interface that allows users to interact with the Hbnb system. It interprets commands and performs actions related to managing properties, users, and bookings within the application.

How to Start
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/Hbnb.git
Navigate to the project directory:

bash
Copy code
cd Hbnb
Start the command interpreter:

bash
Copy code
./console.py

How to Use
Once the command interpreter is running, you can use the following commands:

create: Create a new instance of a class (e.g., User, Place).

lua
Copy code
create <class_name>
show: Display information about an instance by its ID.

php
Copy code
show <class_name> <instance_id>
destroy: Delete an instance by its ID.

php
Copy code
destroy <class_name> <instance_id>
all: Display all instances or all instances of a specific class.

css
Copy code
all
all <class_name>
update: Update the attributes of an instance.

php
Copy code
update <class_name> <instance_id> <attribute_name> "<attribute_value>"
quit or EOF: Exit the command interpreter.

Copy code
quit

Examples
Create a new User instance:

bash
Copy code
create User
Show information about a User instance with ID "123":

bash
Copy code
show User 123
Delete a Place instance with ID "456":

bash
Copy code
destroy Place 456
Display all instances of the Review class:

bash
Copy code
all Review
Update the name attribute of a City instance with ID "789":

bash
Copy code
update City 789 name "Nairobi"
