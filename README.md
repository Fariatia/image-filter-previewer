# To-Do List Application

## Description
This project is a simple and user-friendly **To-Do List** application that allows users to add tasks, display them in a list, and remove tasks upon completion. Tasks are stored locally using the browser's **LocalStorage**, so the list will persist even after refreshing the page or closing the browser.

## Features
- Add tasks to the list by entering text and clicking the **Add Task** button.
- Automatically save tasks in **LocalStorage** so they remain even after page reloads.
- Remove tasks by clicking on them.
- The UI is simple and responsive, providing a clean user experience.

## Technologies Used
- **HTML5**: For the structure of the webpage.
- **CSS3**: For basic styling of the form and task list.
- **JavaScript**: To handle the dynamic task adding, removing, and local storage functionality.
- **LocalStorage**: Used to store tasks persistently in the browser.

## How to Use
1. Open the `index.html` file in any modern web browser.
2. In the input box, type the task you want to add and press the **Add Task** button.
3. The task will appear in the list below. Click on any task to remove it.
4. Tasks are automatically saved in the browser's LocalStorage, so your to-do list will remain even after you close the browser or refresh the page.

## How It Works
- **Add Task**: When you enter a task and click **Add Task**, the task is appended to the list and saved in the browser’s LocalStorage.
- **Remove Task**: Clicking on a task removes it from both the list and LocalStorage.
- **Persistence**: On page load, all previously saved tasks are loaded from LocalStorage and displayed on the page.

## Code Explanation
- **HTML**: Provides the basic structure of the page with an input field, a button, and a task list (`ul`).
- **CSS**: Styles the input, button, and task list items for better readability and aesthetics.
- **JavaScript**: Handles all dynamic functionalities:
  - `addTask()`: Adds a new task to the list and saves it to LocalStorage.
  - `appendTask(task)`: Displays a new task on the list and binds the remove functionality.
  - `removeTask(task)`: Removes the task from the list and deletes it from LocalStorage.
  - `loadTasks()`: Loads the saved tasks from LocalStorage on page load.

## Installation
To run this project locally, follow these steps:
1. Download or clone the repository.
2. Open the `index.html` file in your web browser.

## Future Enhancements
- Add task editing functionality.
- Add due dates and priority levels for tasks.
- Implement a filter to show completed or pending tasks.
- Style improvements for a better user interface and experience.

## License
This project is licensed under the MIT License.
