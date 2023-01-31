# React Notes App

This is a basic notes application built with React. It allows you to create, edit, and delete notes. The notes are saved in local storage so that they persist even after the page is refreshed.

![Alt text](Screenshot_1.png?raw=true "Optional Title")

## Components

- App: The main component that serves as the root component and holds the state for the application.
- Main: The component that displays the active note for editing.
- Sidebar: The component that displays a list of all the notes and allows you to add a new note, delete a note or select a note to be edited.

## Features
- Add new notes.
- Edit existing notes.
- Delete notes.
- Notes persist in local storage.

## Libraries used
- react-uuid: Used to generate unique ids for each note.
- localStorage: Used to store notes in the browser's local storage.
