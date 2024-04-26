Title:TodoList 
----------------------------------------------------------------------------------------------------------------------
Intern Info
Name:Dodali Chandrashekar
ID:ICOD7060
----------------------------------------------------------------------------------------------------------------------
Introduction
The TodoList component is a React component designed to manage a list of tasks. It allows users to add new tasks, mark tasks as done, edit existing tasks, and delete tasks from the list. The component is built using React functional components and utilizes state management with the useState hook.
----------------------------------------------------------------------------------------------------------------------
Implementation
The TodoList component is implemented using React functional components and Bootstrap for styling. It consists of a form to add new tasks, a list to display existing tasks, and options to mark tasks as done, edit tasks, and delete tasks.
----------------------------------------------------------------------------------------------------------------------
Code Explanation
The component starts by importing necessary dependencies such as React, useState hook, FontAwesomeIcon, and CSS files. It then defines the TodoList functional component.

- State Initialization: 
  - `toDo`: Manages the list of tasks.
  - `newTask`: Stores the value of the new task input field.
  - `updateData`: Stores the data of the task being updated.

- Functionality:
  - `addTask`: Adds a new task to the list.
  - `deleteTask`: Deletes a task from the list.
  - `markDone`: Marks a task as done or not done.
  - `cancelUpdate`: Cancels the task update operation.
  - `changeTask`: Updates the task data when editing.
  - `updateTask`: Updates the task in the list after editing.

- Render:
  - Renders the input field and buttons for adding or updating tasks.
  - Renders the list of tasks with options to mark as done, edit, and delete.
----------------------------------------------------------------------------------------------------------------------
Functionality
- Add Task:
  - Users can input a task in the text field and click the "Add Task" button to add it to the list.
- Delete Task:
  - Users can delete a task by clicking the delete icon next to the task.
- Mark Task as Done:
  - Users can mark a task as done or not done by clicking the circle icon next to the task.
- Edit Task:
  - Users can edit a task by clicking the edit icon next to the task. This opens the task for editing.
- Update Task:
  - Users can update the task after editing by clicking the update button.
----------------------------------------------------------------------------------------------------------------------
Usage
To use the TodoList component in your React application:
1. Import the TodoList component into your React component file.
2. Add the TodoList component to your JSX markup.
----------------------------------------------------------------------------------------------------------------------
Conclusion
The TodoList component provides a simple and intuitive interface for managing tasks within a React application. It offers essential functionalities such as adding, deleting, marking tasks as done, and editing tasks. With its clean design and easy-to-understand code, it serves as a practical solution for implementing a todo list feature in web applications.
