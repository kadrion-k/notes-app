# Notes App

A simple web-based note-taking application where users can add, edit, and delete notes. The app allows users to manage their notes in a user-friendly interface. Notes are created dynamically and are editable with a rich-text area.

## Description

This **Notes App** lets users add notes, edit them, and delete them. It is a clean and simple interface with a fixed "Add Note" button that creates a new note each time it's clicked. The notes can be edited in a textarea and can be deleted with a trash icon. This app uses basic HTML, CSS, and JavaScript to provide an interactive experience.

## Features

- **Add New Note**: The user can add a new note by clicking the "Add note" button.
- **Edit Notes**: Notes can be edited by toggling between a view and an edit mode with the help of an edit button.
- **Delete Notes**: Users can delete a note by clicking on the trash icon in the note header.
- **Persistent Layout**: The layout adjusts dynamically as notes are added, edited, or removed.

## Technologies Used

- **HTML**: Structure of the notes app, including buttons, text areas, and containers.
- **CSS**: Styling to create an aesthetically pleasing and user-friendly layout for the app.
- **JavaScript**: Provides functionality to add, edit, and delete notes dynamically.

## How It Works

1. **Add a Note**:
   - When the user clicks the "Add note" button, a new note is created dynamically with an empty textarea.
   
2. **Edit a Note**:
   - Each note has an "Edit" button. When clicked, it toggles between a read-only view (where the note content is displayed) and an editable textarea.

3. **Delete a Note**:
   - Each note has a "Delete" button (represented by a trash icon). Clicking this button removes the note from the screen.

4. **Dynamic Layout**:
   - As the user adds, edits, or deletes notes, the layout automatically adjusts. The newly created notes are appended to the body of the page, while existing notes can be interacted with.
