# 011 Update a JSON File

In the language of your choice, write code that maintains a JSON file by appending a new entry each time the program is run.

**Task:**

- Create a script/program that:
  - Checks for the existence of [011-data.json](/assets/011-data.json).
    - If the file does not exist, it should be created and initialized with an empty array `[]`.
  - Reads the existing JSON data from the file.
  - Appends a new object to the array with the following structure:
    ```json
    {
      "timestamp": "<current ISO timestamp>",
      "message": "This is entry number <n>"
    }
    ```
    - `<current ISO timestamp>` should be the current date and time in ISO 8601 format.
    - `<n>` should be the next sequential number based on the existing entries.
  - Writes the updated array back to [011-data.json](/assets/011-data.json).
