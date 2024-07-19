Run the Project using "python3 app.py" 

The project runs on:-
  localhost/http://127.0.0.1:5000

Explanation:-
This Flask web application manages a to-do list using blockchain technology. It defines two classes: Block, which represents a single task in the blockchain, and Blockchain, which manages a chain of tasks.

Block Class: Represents each to-do item with attributes like index, previous_hash, timestamp, task, hash, and completed status.
Blockchain Class: Manages the list of tasks with methods to add tasks, mark tasks as completed, remove tasks, and validate the chain's integrity. It starts with a "Genesis Block" and uses SHA-256 hashing to ensure data security.
The Flask app provides endpoints to:

Add a new task (/add_task).
Mark a task as completed (/complete_task).
Remove a task (/remove_task).
Retrieve the entire blockchain (/get_chain).
View the blockchain through a web page (/view_chain).
The app runs in debug mode, allowing users to interact with the to-do list through a web interface and manage tasks using the blockchain.

Summary:-
Component	Function:-
Block Class	Defines the structure of a single to-do task with properties and a hash.
Blockchain Class	Manages the list of tasks with methods for adding, completing, and removing tasks.
/add_task	Adds a new task to the blockchain.
/complete_task	Marks a specific task as completed.
/remove_task	Removes a task from the blockchain.
/get_chain	Retrieves the full list of tasks as a JSON object.
/view_chain	Displays the blockchain through a web page.

The output is viewed as a simple HTML page in the browser. 
