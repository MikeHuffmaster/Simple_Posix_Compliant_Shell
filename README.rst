# CustomShell

CustomShell is a POSIX-like shell written in C, designed to provide a foundational shell environment for executing commands, managing processes, and exploring shell scripting concepts. This project was implemented in stages, focusing on core utilities, command parsing, and process management.

## Features

- **Core Built-in Commands:**
  - `cd`: Change the current working directory.
  - `exit`: Exit the shell.
  - `unset`: Unset internal shell variables.

- **Command Execution:**
  - Support for running external programs.
  - Background process management.

- **Parsing and Redirection:**
  - Input and output redirection.
  - Basic command parsing for seamless execution.

- **Error Handling:**
  - Graceful handling of invalid commands and syntax errors.
  - Display of exit statuses for executed commands.

## How to Build

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customshell.git
   cd customshell
   ```

2. Compile the source code using `make`:
   ```bash
   make
   ```

3. Run the shell:
   ```bash
   ./customshell
   ```

## Usage

- Start the shell by running `./customshell`.
- Use it like a standard shell to:
  - Navigate directories: `cd <path>`
  - Run programs: `ls`, `echo`, etc.
  - Set and unset internal variables: `unset <variable>`
  - Exit the shell: `exit`

## Example
```bash
$ ./customshell
CustomShell> cd /home/user
CustomShell> ls
file1.txt  file2.txt
CustomShell> unset MY_VAR
CustomShell> exit
```

## Project Structure

- `main.c`: Entry point of the shell.
- `parser.c`: Handles command parsing and tokenization.
- `builtin.c`: Implements built-in commands like `cd` and `unset`.
- `process.c`: Manages process creation and execution.
- `Makefile`: Automates the build process.

## Contributions

This project is open for contributions to extend its functionality and improve its design.

To contribute:
1. Fork the repository.
2. Create a feature branch.
3. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by foundational shell concepts and POSIX standards.


