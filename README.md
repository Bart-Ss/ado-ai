# Python TODO CLI Application

A simple command-line todo list application written in Python that allows you to manage your tasks through the terminal.

## Features

- Add new tasks
- List all tasks with their completion status
- Data persistence using JSON storage

## Usage

```bash
# Add a new task
python src/todo.py add "Complete the project documentation"

# List all tasks
python src/todo.py list

# Show help
python src/todo.py --help
```

## Installation

No external dependencies are required. Just clone the repository and ensure you have Python 3.x installed.

## File Structure

- `src/todo.py` - Main CLI application
- `tasks.json` - JSON file for task storage
- `requirements.txt` - Project dependencies (uses only standard library)

