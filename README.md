# Notes App (Java File I/O)

## What I Did
- Created a Java console-based Notes App using **File I/O**.
- Implemented features to:
  - Write new notes
  - View saved notes
  - Clear all notes
  - Exit the application
- Used `FileWriter`, `FileReader`, and `BufferedReader` for file operations.

## How It Works
1. Displays a menu with 4 options:
   - **Write a note** → Appends the note to `notes.txt`.
   - **View notes** → Reads and displays all saved notes from the file.
   - **Clear notes** → Erases all content from `notes.txt`.
   - **Exit** → Closes the app.
2. Notes are stored in `notes.txt` so they are available even after restarting the program.
3. Runs in a loop until the user chooses to exit.

## Example Output
![Screenshot](images/menu.png)
