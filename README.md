# Todo_list_app
# To-Do List Application

A simple command-line To-Do List application written in Python. This application allows users to add, view, mark as complete, delete tasks, and receive reminders for upcoming tasks.

## Features

- **Add Tasks**: Add tasks with optional due dates.
- **View Tasks**: Display all tasks with their status and due dates.
- **Mark Tasks Complete**: Mark tasks as completed.
- **Delete Tasks**: Remove tasks from the list.
- **Reminders**: Get reminders for tasks due within the next 24 hours or overdue by less than 10 minutes.
- **Persistent Storage**: Tasks are saved to a CSV file (`tasks.csv`) for persistence between sessions.

## Installation

1. **Prerequisites**:
   - Python 3.x installed on your system.

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/todo-list-app.git
   cd todo-list-app
## Run the Application:
- python todo_list.py
## Usage
**Main Menu:**

**Choose an option from the menu:**

1. View Tasks
2. Add Task
3. Mark Task Complete
4. Delete Task
5. Check Reminders
6. Exit

- **Adding a Task:**
Enter the task description.
Optionally, provide a due date in the format YYYY-MM-DD HH:MM.
- **Marking a Task Complete:**
View the list of tasks and enter the ID of the task to mark as complete.
- **Deleting a Task:**
View the list of tasks and enter the ID of the task to delete.
- **Reminders:**
The application will notify you of tasks due within the next 24 hours or overdue by less than 10 minutes.

## File Structure

todo-list-app/

├── todo_list.py       # Main Python script

├── tasks.csv          # CSV file for storing tasks (auto-generated)

└── README.md          # Documentation
## Functions
- **load_tasks():** Loads tasks from the CSV file.
- **save_tasks(tasks):** Saves tasks to the CSV file.
- **display_tasks(tasks):** Displays all current tasks.
- **get_next_id(tasks):** Generates the next unique ID for a new task.
- **add_task(tasks):** Adds a new task to the list.
- **mark_task_complete(tasks):** Marks a task as completed.
- **delete_task(tasks):** Deletes a task from the list.
- **check_reminders(tasks):** Checks for upcoming tasks and provides reminders.
## Example Usage

## Run
- **pyth on task_manager.py**

--- To-Do List Manager ---
1. View Tasks
2. Add Task
3. Mark Task Complete
4. Delete Task
5. Check Reminders
6. Exit
Enter your choice: 

