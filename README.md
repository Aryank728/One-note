Preview of the repo: https://onennote.netlify.app
# Getting Started with Create React App

# Notes App

This is a simple web-based note-taking application built with React. You can create and manage notes, search for specific notes, and even toggle a dark mode. 

# Installation

To run this project on your local machine, you need to have Node.js and npm (Node Package Manager) installed. If you don't have them, you can download and install them from [Node.js official website](https://nodejs.org/).

1. Clone this repository to your local machine using the following command:

The following packages will be installed:
```bash
react: ^17.0.2
react-dom: ^17.0.2
react-icons: ^4.2.0
nanoid: ^3.1.19
react-scripts: 4.0.3 (for development)
```

Start the development code: ```npm start```
Open your web browser and go to http://localhost:3000 to use the Notes App.

Usage
Here's how to use the Notes App:
Click the "Add Note" button to create a new note.
Enter the note text and save it.
You can search for specific notes by typing in the search bar.
To delete a note, click the trash can icon on the note.
Toggle the dark mode by clicking the "Dark Mode" button in the header.

# Project Structure

The project structure is as follows:
```
App.js: The main component that orchestrates the entire app.
components/NotesList.js: Renders the list of notes and handles adding and deleting notes.
components/Header.js: The app's header with a title and dark mode toggle.
components/Note.js: Displays an individual note with its text, date, and delete functionality.
components/Search.js: Provides a search bar to filter notes.
index.js: The entry point of the application.
index.css: Contains the styles for the entire application.
```
# License
```bash
This project is open-source and is licensed under the MIT License. Feel free to use and modify it as needed.
```

# Acknowledgments
```bash
This project was created using React, a JavaScript library for building user interfaces.
Enjoy using the Notes App for your note-taking needs!
```
