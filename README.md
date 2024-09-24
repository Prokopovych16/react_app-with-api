# React Todo App with API (complete)

   - [DEMO LINK](https://Prokopovych16.github.io/react_app-with-api/)

This React-based Todo App allows users to manage their tasks efficiently. It includes essential features such as adding, editing, deleting, and filtering tasks. The app interacts with a REST API to handle persistent data storage and retrieval. Here's a breakdown of the key features:

**Features:**
- Fetching Todos:
  - On initial load, the app fetches the list of todos from an external API and displays them in a structured format.
  - Error handling is implemented to notify users if the todos can't be loaded.
- Adding Todos:
  - Users can add a new todo by typing in the input field and hitting enter. The app checks for non-empty titles before sending the todo to the API.
  - Optimistic UI updates are used by temporarily showing the new todo until the API request is completed.
- Editing Todos:
  - Users can double-click on a todo to edit its title. Once edited, the app sends a PATCH request to update the todo on the server.
  - Inline updates ensure that the UI is updated immediately after the change.
- Deleting Todos:
  - Users can delete individual todos, as well as bulk delete all completed todos.
  - The app sends a DELETE request for each todo that needs to be removed from the list.
- Filtering Todos:
  - Todos can be filtered by three options: All, Active, and Completed.

**Tech Stack:**
- **React:** For building the UI components.
- **TypeScript:** For static typing and error prevention during development.
- **REST API:** To handle CRUD operations for todos.
- **SCSS:** For styling the app.

This app serves as a solid base for managing tasks with real-time interactions and server-side synchronization.