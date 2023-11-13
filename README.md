# Simple Shell Project

## Introduction

Welcome to the Simple Shell project! This project is a minimalist implementation of a Unix-like shell in the C programming language. The Simple Shell provides a command-line interface for users to interact with their computer, execute programs, and manage files and directories. It is designed to be a learning tool and a starting point for those interested in understanding how shells work.

This project is part of the 0x16 curriculum, and it is an opportunity to apply your knowledge of C programming and system calls to create a functional shell.

## Features

- Basic command execution: Run simple commands and system utilities.
- Shell prompt: Display a user-friendly prompt for entering commands.
- Path resolution: Search for executable files in the system's PATH.
- Built-in commands: Implement a set of built-in commands (e.g., `cd`, `exit`, `help`).
- Signal handling: Handle signals such as Ctrl+C gracefully.
- Redirection and pipelines: Implement basic input and output redirection and pipelines.
- Environment variables: Support environment variable expansion.
- Error handling: Provide meaningful error messages for user input and system calls.

## Getting Started

### Prerequisites

Before you get started with the Simple Shell project, make sure you have the following prerequisites installed on your system:

- C Compiler (e.g., GCC)
- Git (for version control)

### Installation

To install the Simple Shell project on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/simple-shell.git
   ```

2. Change to the project directory:

   ```bash
   cd simple-shell
   ```

3. Compile the shell program:

   ```bash
   gcc -o shell shell.c
   ```

4. Run the shell:

   ```bash
   ./shell
   ```

Now you should have a working Simple Shell running on your system.

## Usage

To use the Simple Shell, simply enter commands at the shell prompt. Here are some examples of how to use the shell:

- Run a simple command:

  ```
  $ ls -l
  ```

- Use built-in commands:

  ```
  $ cd /path/to/directory
  $ help
  $ exit
  ```

- Redirect input and output:

  ```
  $ cat input.txt > output.txt
  ```

- Create pipelines:

  ```
  $ ls | grep keyword
  ```
