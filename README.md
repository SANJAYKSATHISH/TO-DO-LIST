# TO-DO-LIST
HTML CODE
This HTML code sets up a basic "To Do List" web app with the following features:

1. Metadata and Styles:
   - Defines the document as HTML5 and sets the character encoding to UTF-8.
   - Ensures compatibility with modern browsers and mobile devices.
   - Links to an external CSS file for styling.

2. Body Content:
   - Contains a heading and an input area for adding tasks.
   - Includes a text input field and an "Add" button.
   - Features an unordered list (`<ul>`) for displaying tasks.

3. JavaScript Integration:
   - Links to an external JavaScript file for handling task addition and interactions.

JAVA SRCIPT
Overview
Elements Access:
inputBox`: Captures user input for new tasks.
addBtn`: Button to add or edit tasks.
todoList: Container for displaying tasks.
Global Variable:
editTodo: Stores the event object for editing a task.

 Functions

1. Add Task:
   addTodo()`: Adds a new task to the list or updates an existing task if the button text is "Edit".
   Validation: Ensures the input is not empty.
   Task Creation: Creates a list item with a checkbox, task text, and buttons for editing and deleting.
   Local Storage: Saves the new task to local storage if adding, and updates it if editing.

2. Update Task:
   updateTodo(e)`: Handles clicks on "Edit" and "Remove" buttons.
   Remove: Deletes the task from the list and local storage.
   Edit: Populates the input box with the task text for editing and changes the button to "Edit".

3. Local Storage Management:
   saveLocalTodos(todo)`: Stores new tasks in local storage.
   getLocalTodos(): Retrieves and displays tasks from local storage when the page loads.
   deleteLocalTodos(todo): Removes a task from local storage.
   editLocalTodos(todo): Updates a task in local storage after editing.

 Event Listeners

DOMContentLoaded: Ensures tasks are loaded from local storage when the page loads.
click`: Adds new tasks or updates existing ones based on the button clicked.

Functionality

Task Addition: Users can enter a task, which is added to the list and saved.
Task Editing: Existing tasks can be edited and updated.
Task Deletion: Tasks can be removed from both the list and local storage.
Persistence: Tasks are stored in local storage, making them persistent across page reloads.

This code provides a robust solution for managing a to-do list with basic CRUD operations and local storage integration, allowing users to interact with and manage their tasks effectively.

STYLE:
This CSS stylesheet enhances a to-do list web app with a clean, modern look:

Font: Uses Poppins from Google Fonts for a sleek, modern text style.
General Reset: Removes default margins and paddings, and sets consistent box-sizing.
Body: Applies a light gray background color.
Container: Centers content vertically and horizontally with Flexbox and adds top margin.
Input Container: Limits width, centers content, and styles inputs with no borders, rounded corners, and padding. The button has a green background with white text and changes color on hover.
List Items: Styles list items with no bullets, a light border, rounded corners, and a white background. Items have a hover effect for visual feedback.
Buttons: General button styling includes no borders, bold font, and pointer cursor. Delete and edit buttons have distinct colors.
Checkbox: Adds margin to the right of checkboxes for proper spacing.

This CSS provides a user-friendly, visually appealing design for the to-do list app.
