# 014 Write a CLI with Help Option

In the language of your choice, write code to create a command-line interface (CLI) application that supports a single command and provides help information.

**Task:**

- Create a script/program that:
  - Accepts a single command, such as `greet`.
  - Supports the `-h` and `--help` flags to display usage information.
  - When the `greet` command is invoked, prints a greeting message to the screen.

**Usage Examples:**

```bash
$ cli_app greet
Hello, User!

$ cli_app -h
Usage: cli_app [command]

Commands:
  greet    Display a greeting message

Options:
  -h, --help    Show this help message and exit
```
**Note:**
* You might need to run the script with `node cli_app.js` or `python cli_app.py` at the beginning.
* Consider how you could make it work without needing to prefix the command with `node` or `python` before your file name.
* 
