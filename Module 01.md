# Module 1: Getting Started with Shell & Bash

### Concepts:
#### What is a Shell? What is Bash?
**What is a Shell?**
A shell is a command-line interpreter that provides a user interface for the operating system's kernel. It allows users to interact with the OS by typing commands.

**In simple terms:**
The shell takes your commands and tells the operating system what to do.
You type commands -> shell interprets them -> OS performs actions.

#### Common Unix/Linux Shells
| Shell | Description |
|-------|-------------|
| `sh`  | Original Bourne Shell - the standard Unix shell |
| `bash`| **Bourne Again Shell** - enhanced and backward-compatible version of `sh` |
| `zsh` | Z Shell - modern shell with advanced features like auto-suggestions and plugins |
| `fish`| Friendly Interactive Shell - known for its user-friendly design and syntax highlighting |
| `dash`| Debian Almquist Shell - lightweight and fast, used in some Linux systems (e.g., Debian/Ubuntu for scripting) |

#### What is Bash?
Bash stands for Bourne Again Shell. It is a widely used shell on Linux and macOS systems. Each is both an interactive command interpreter and a scripting language.
# Bash Scripting Guide

### Common Unix/Linux Shells

**What is Bash?**
- Bash stands for Bourne-Again Shell. It is a widely used shell on Linux and macOS systems. Bash is both an interactive command interpreter and a scripting language.

**Features of Bash:**
- Command history
- Tab completion
- Scripting capabilities
- Customizable environment
- Supports variables, loops, conditionals, functions
- Portable across many Unix-like systems

**Example Bash Command:**
bash

      echo "Hello from Bash!"

**Example Bash Script (hello.sh):**
bash

      #!/bin/bash
      echo "This script is running in Bash!"

**How to Check Which Shell You're Using**
Run this in your terminal:
bash
      
      echo $SHELL

Or check which shell is currently active:
bash

      ps -p $$ -o comm=

**Changing Your Default Shell**
You can change your default shell using the chsh command:

    chsh -s /bin/bash

Make sure the desired shell is installed before switching.

### Terminal vs Shell vs Bash - What's the Difference?

| Term       | Description                                                                 |
|------------|-----------------------------------------------------------------------------|
| **Terminal** | A program that gives you access to the shell. It's the "interface" where you type commands (e.g., GNOME Terminal, iTerm2, Windows Terminal). |
| **Shell**    | A command-line interpreter that processes commands typed in the terminal and communicates with the operating system. There are many shells like `sh`, `bash`, `zsh`, `fish`, etc. |
| **Bash**     | A specific and widely used shell called "Bourne-Again Shell". It is backward-compatible with the original Bourne shell (`sh`) and includes enhanced features. |

### Analogy

Think of it like this:

- The **terminal** is your steering wheel.
- The **shell** (like Bash) is the engine that makes the car move.
- You type commands into the **terminal**, which passes them to the **shell** (e.g., Bash), and then the OS does the work.

### Example Commands in Bash via Terminal

    echo "Hello from Bash!" # This runs in the shell (Bash), through the terminal

### Summary Table

| Concept   | Type        | Purpose |
|-----------|-------------|---------|
| Terminal  |Application  | Provides a window to interact with the shell |
| Shell     |Interpreter  | Acepts and executes commands |
| Bash      | Shell       | A popular shell with advanced features |
