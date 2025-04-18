# Task Tracker CLI - PHP Application (Inspired by roadmap.sh)

This is a lightweight command-line application built with PHP to help you manage your tasks with ease. It lets you create, view, update, and delete tasks, all stored locally in a simple JSON file. This README.md walks you through the steps to install, set up, and use the application, and gently explains all the features it offers.

## Features:

- **Add, Update, and Delete tasks**
- **Mark a task as in progress or done**
- **List all tasks**
- **List all tasks that are done**
- **List all tasks that are not done**
- **List all tasks that are in progress**

**Project Details**: https://roadmap.sh/projects/task-tracker

## The list of commands and their usage is given below:

- Adding a new task
```bash
   php task-cli add "Buy groceries"
```

- Updating and deleting tasks
```bash
   php task-cli update 1 "Buy groceries and cook dinner"
   php task-cli delete 1
```

- Marking a task as in progress or done
```bash
   php task-cli mark-in-progress 1
   php task-cli mark-done 1
```

- Listing all tasks
```bash
   php task-cli list
```
- Listing tasks by status
```bash
   php task-cli list done
   php task-cli list todo
   php task-cli list in-progress
```


## Installation


1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/mdahanaf/tasks-cli.git
   ```

2. And done. Now you can easily add your first task via CLI 🚀
     - For example
         ```bash
        php task-cli add "Buy groceries"
         ```
  