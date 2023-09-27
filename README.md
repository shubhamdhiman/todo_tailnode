# React TODO App Assignment

## Overview

This is a simple offline TODO app built with React JS, designed to meet the specified requirements.

## Key Features

- A simple input bar to add Todo(s) on pressing the Enter key.
- A list of TODO cards where each todo is appended on creation.
- Clicking on a TODO card marks it as complete and moves it to the bottom of the list.
- The active TODO cards appear in order of creation (most recent on top).
- Completed todo cards appear in order of completion (most recent on top).
- A reset button clears all Todo(s) and returns to the initial state.
- The app works offline and doesn't lose data on a browser refresh.

## Implementation

### Components

- `TodoInput.js`: Handles adding new TODO items.
- `TodoList.js`: Displays the list of TODO items.
- `TodoCard.js`: Represents individual TODO items.
- `App.js`: Manages the state and integrates the components.

### Local Storage Integration

- TODOs are loaded from local storage on app start.
- TODOs are saved to local storage when added, completed, or reset.

### Styling

Basic CSS styles are applied to the app for a clean and simple design.

## Usage

1. Enter a new TODO item in the input bar and press "Enter" to add it.
2. Click on a TODO card to mark it as complete.
3. Completed TODOs are moved to the bottom of the list.
4. Click the "Reset" button to clear all TODOs and start over.

## Compatibility

The app is designed to work in the latest versions of Google Chrome and Firefox.
## Previews
![1](https://github.com/shubhamdhiman/todo_tailnode/assets/18380165/3314bbe9-bfd7-4837-bfb8-72f39d7ee3df)
![2](https://github.com/shubhamdhiman/todo_tailnode/assets/18380165/117240b6-a0a2-4712-bf29-b16d2113d30a)

## GitHub Repository

You can find the code for this assignment in the following public GitHub repository:
[Link to GitHub Repository](https://github.com/yourusername/todo-app)

## Additional Notes

- Documentation is kept minimal for brevity.
- Local storage integration ensures data persistence.
- Styling can be customized to fit design preferences.
- Edge cases and assumptions are documented in the code.

For any questions or clarifications, please feel free to contact me.

Enjoy using the TODO app!
