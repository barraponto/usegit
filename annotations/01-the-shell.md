Annotations for Lesson 1: The Shell

What is the terminal?
---
Terminal: The terminal is a program that exposes the command-line shell to users, enabling interaction through text-based commands.

What is a shell?
---
Shell: A shell serves as an interface to the computer. Graphical shells provide icons and windows, while command-line shells facilitate text input and output operations.

What is a command?
---
Command: Commands are textual representations of user requests to the computer. For instance, an email can be sent using a command like `mail --subject="i need a raise" boss@company.com < ./contents.txt`.

What is an interpreter?
---
Interpreter: An interpreter is a program that processes and executes user input programs. It handles logic, including conditionals and loops, making it a vital tool for executing shell scripts.

What is the PATH?
---
PATH: The PATH is an environment variable that lists directories where the shell searches for programs. The shell uses the first match it finds for program execution.

What is an environment variable?
---
Environment variable: Environment variables are named values accessible to shell commands. They include established conventions like `PWD`, `PATH`, and `PS1`, and users can create their own variables.

How can I see the environment variables?
---
To view current environment variables, use the `env` command.

How can I configure those variables?
---
Variables can be configured using files like `.bashrc` or `.zshrc`, allowing customization of the shell environment.

What shell am I running?
---
Determine the active shell by using the command `echo $0`.
