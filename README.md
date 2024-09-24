# Task Tracker CLI

A simple command-line interface (CLI) to help you track and manage your tasks. This application allows you to add, update, delete, and list tasks, as well as mark them as "in-progress" or "done". Tasks are stored in a JSON file.
Features

    Add Tasks: Add new tasks with a description.
    Update Tasks: Update the description of a task.
    Delete Tasks: Delete a task by its ID.
    Mark Tasks: Mark tasks as "in-progress" or "done".
    List Tasks: List all tasks or filter by their status ("todo", "in-progress", "done").
    Persistent Storage: Tasks are stored in a JSON file, allowing them to be saved across sessions.

# Task Properties

Each task contains the following properties:

    id: Unique identifier for the task.
    description: The description of the task.
    status: The status of the task (todo, in-progress, done).
    createdAt: The timestamp when the task was created.
    updatedAt: The timestamp when the task was last updated.
