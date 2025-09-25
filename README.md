# SimpleOS

A simple operating system emulator with command shell written in Python.

## Description

SimpleOS is an educational project that demonstrates basic operating system principles. It includes a file system, process management, and a simple text editor.

## Features

- 📁 File and directory operations
- 💻 Command shell interface
- 🔄 Process management
- ✏️ Built-in text editor
- 🧵 Multithreading support

## Commands

| Command | Description |
|---------|-------------|
| `ls` | List files in current directory |
| `cd <path>` | Change directory |
| `mkdir <name>` | Create a new directory |
| `rm <name>` | Remove a file |
| `touch <name>` | Create an empty file |
| `fake <name>` | Open text editor |
| `run <name>` | Start a process |
| `help` | Show help message |
| `exit` | Shutdown the system |

## Installation and Usage

```bash
# Clone the repository
git clone <your-repo-url>
cd Easy

# Run SimpleOS
python main.py
```

## Requirements

- Python 3.6+
- Standard libraries: `os`, `time`, `threading`

## Example Usage

```
Welcome to SimpleOS! Type 'help' for commands.
D:\Cursor projects\Easy $ ls
main.py
README.md
D:\Cursor projects\Easy $ mkdir test
Directory created: test
D:\Cursor projects\Easy $ cd test
D:\Cursor projects\Easy\test $ touch hello.txt
File created: hello.txt
```

## Author

Educational project for learning operating system fundamentals
