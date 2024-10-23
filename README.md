# To-Do List Application

This is a simple command-line To-Do List application written in C++. It allows users to add tasks, mark them as completed, and view all tasks in the list.

## Features

- **Add Tasks**: Users can add new tasks with descriptions.
- **Mark Tasks as Completed**: Users can mark existing tasks as completed.
- **View Tasks**: Users can view all tasks, with an indication of which are completed.
- **Menu Interface**: A simple text-based menu allows users to navigate the application.

## Code Structure

- **Task Class**: Represents an individual task with a description and completion status.
- **ToDoList Class**: Manages a list of tasks, including adding, completing, and viewing tasks.
- **Main Function**: Handles user input and interacts with the ToDoList class.

## Getting Started

### Prerequisites

- A C++ compiler (e.g., g++, clang++)
- Basic understanding of C++ and command-line usage

### Compilation

To compile the program, use the following command in your terminal:

```bash
g++ -o todo_list todo_list.cpp
```

### Running the Application

After compiling, you can run the application with:

```bash
./todo_list
```

### Menu Options

- **1. Add Task**: Enter a description for the new task.
- **2. Mark Task as Completed**: Select a task number to mark it as completed.
- **3. View Tasks**: Display all tasks with their completion status.
- **4. Exit**: Exit the application.

## Example Usage

```plaintext
To-Do List Menu:
1. Add Task
2. Mark Task as Completed
3. View Tasks
4. Exit
Enter your choice: 1
Enter task description: Buy groceries
Task added: Buy groceries

To-Do List Menu:
1. Add Task
2. Mark Task as Completed
3. View Tasks
4. Exit
Enter your choice: 3
Current Tasks:
1. Buy groceries
```

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Any improvements or additional features are welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for details.
