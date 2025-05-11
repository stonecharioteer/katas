# 015 CLI Append to JSON File

In the language of your choice, write code to create a command-line interface (CLI) application that appends data to a JSON file.

**Task:**

- Create a script/program that:
  - Accepts command-line arguments for the path to a JSON file and key-value pairs to append.
  - If the specified JSON file does not exist, it should be created and initialized with an empty array `[]`.
  - Parses the existing JSON data from the file.
  - Appends a new object constructed from the provided key-value pairs to the array.
  - Writes the updated array back to the file.

**Usage Examples:**

```bash
$ cli_app --file data.json --name Alice --age 30
Data appended successfully.

$ cli_app --file data.json --name Bob --age 25
Data appended successfully.
```
After running the above commands, the data.json file should contain:
```json
[
  {"name": "Alice", "age": 30},
  {"name": "Bob", "age": 25}
]
```
**Note**:
* This exercise is useful for understanding how to build CLI applications that accept parameters and manipulate JSON files.
* Be mindful of character encoding. Ensure your program reads and writes the file using UTF-8 encoding to support all characters.
* By default, JSON data written to a file may be compacted into a single line without indentation, making it less readable. To enhance readability, consider implementing pretty-printing by adding indentation when writing JSON data to the file.
