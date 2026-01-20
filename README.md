# Command-Line Todo List App

A simple Python command-line application for managing a todo list.
Tasks are stored locally in a `tasks.txt` file and can be added, listed, or removed using command-line arguments.

---

## Features

* Add new tasks
* List all existing tasks
* Remove tasks by their index
* Lightweight and dependency-free (uses Python standard library only)

---

## Requirements

* Python 3.x

---

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/cjd2207/<your-repo-name>.git
   ```
2. Navigate into the project directory:

   ```bash
   cd <your-repo-name>
   ```

---

## Usage

Run the script using Python:

```bash
python todo.py [options]
```

(Replace `todo.py` with the actual filename if different.)

---

## Command-Line Options

### Add a task

```bash
python todo.py --add "Buy groceries"
```

or

```bash
python todo.py -a "Buy groceries"
```

---

### List all tasks

```bash
python todo.py --list
```

or

```bash
python todo.py -l
```

Example output:

```
1. Buy groceries
2. Finish homework
```

---

### Remove a task

```bash
python todo.py --remove 1
```

or

```bash
python todo.py -r 1
```

Removes the task at the specified index.

---

## Data Storage

Tasks are stored in a plain text file named `tasks.txt` in the same directory as the script. Each task is saved on a new line.

---

## Notes

* If `tasks.txt` does not exist, it will be created automatically when adding a task.
* Removing a task rewrites the file without the selected task.
* Indexing starts at **1**, not 0.

---

## License

This project is open source and available under the MIT License.

<img width="1182" height="656" alt="image" src="https://github.com/user-attachments/assets/e3e342c4-d0dc-4a11-8457-367db47c076f" />
