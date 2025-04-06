# TODO Task Tracker CLI - PHP Application

This is a simple command-line interface (CLI) application written in PHP for managing tasks. It allows users to create, view, update, and delete tasks, as well as manage their task list through a local JSON file. This README provides detailed information on how to install, configure, and use the application, along with its full set of functionalities.

## Features:

- **Add, Update, and Delete tasks**
- **Mark a task as in progress or done**
- **List all tasks**
- **List all tasks that are done**
- **List all tasks that are not done**
- **List all tasks that are in progress**

**Project Idea**: https://roadmap.sh/projects/task-tracker

## The list of commands and their usage is given below:

# Adding a new task
task-cli add "Buy groceries"
# Output: Task added successfully (ID: 1)

# Updating and deleting tasks
task-cli update 1 "Buy groceries and cook dinner"
task-cli delete 1

# Marking a task as in progress or done
task-cli mark-in-progress 1
task-cli mark-done 1

# Listing all tasks
task-cli list

# Listing tasks by status
task-cli list done
task-cli list todo
task-cli list in-progress



## Installation


1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/mdahanaf/tasks-cli.git
   ```
2. Run `setup.sh` script
    - On UNIX machine probably u need to first add permission to execute

     ```bash
     chmod -x setup.sh
     ```

    And then run script
    ```bash
   ./setup.sh
   ```
3. Now u can easily add your first task via CLI 🚀
     - Example
         ```bash
        task-cli add "Buy groceries"
         ```
  