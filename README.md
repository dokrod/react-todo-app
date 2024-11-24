[Demo link] https://dokrod.github.io/react_todo-app-with-api/

# React TypeScript To-Do App

This project is a **React TypeScript To-Do Application** that allows users to manage their tasks. It demonstrates modern React patterns, hooks, state management, and component-based architecture.

---

## Features

- **Add, Update, and Delete To-Dos**: Manage your tasks effectively with simple interactions.
- **Filter Tasks**: Filter tasks by active, completed, or all states.
- **Error Notifications**: Inform users about errors during operations.
- **Bulk Actions**: Toggle all tasks as completed or incomplete.
- **Temporary Task Handling**: Display temporary tasks before adding them to the list.
- **Responsive UI**: Clean and user-friendly interface using CSS.

---

## Components Overview

### 1. **Main Components**
- **App**: Main entry point of the application, handling state and rendering.
- **Header**: Includes input for adding new tasks and toggling bulk task completion.
- **Footer**: Allows filtering tasks and bulk deletion of completed tasks.
- **TodoItem**: Renders each individual task with options to update or delete it.
- **ErrorNotification**: Displays error messages for failed operations.
- **UserWarning**: Warns the user when no valid user ID is detected.

### 2. **Custom Hook**
- **useTodos**: Manages the state and logic of all to-dos, including CRUD operations, filtering, and error handling.

---

## Technologies Used

- **React**: Component-based UI framework.
- **TypeScript**: For static type checking and safer code.
- **React Hooks**: For managing state and side effects.
- **Bulma**: Styling with a responsive design approach.
