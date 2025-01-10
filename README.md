# To-Do-list
A simple and interactive web-based To-Do list application that allows users to add tasks, edit tasks, delete tasks, and mark tasks as completed. This app provides a clear and functional interface to track the progress of your tasks.

#Features
Add new tasks
Mark tasks as completed
Edit existing tasks
Delete tasks
Display counters for completed and uncompleted tasks
Responsive and modern design
Files
This project consists of three main files:

index.html: Contains the structure of the page.
style.css: Defines the styling and appearance of the To-Do list.
script.js: Handles the functionality and interactivity of the To-Do list.
Installation and Setup
Clone or download the repository to your local machine.

Open the index.html file in a web browser to view the To-Do list application.

#Usage
Add a task:

Type your task in the input box and click the "Add" button or press the Enter key.
Mark task as completed:

Check the checkbox next to a task to mark it as completed. This will strike-through the task text and update the counters.
Edit a task:

Click the "Edit" button next to a task to change its content. You will be prompted to edit the task.
Delete a task:

Click the "Delete" button next to a task to remove it from the list. You will be asked for confirmation before the task is deleted.
Task Counter:

The "Completed" and "Uncompleted" counters will update automatically as tasks are marked or unmarked as completed.
#Code Breakdown
#HTML (index.html)
A basic structure with a heading, input field, task list, and task counter.
An "Add" button to trigger the addition of tasks.
The task list is displayed dynamically using JavaScript.
#CSS (style.css)
Defines the appearance of the To-Do list, including a gradient background, a centered container, and distinct styles for tasks.
The completed tasks are styled with a line-through effect and a gray color.
The button and input field have hover effects and are responsive to user interaction.
#JavaScript (script.js)
Handles the main functionality, such as adding tasks, editing tasks, deleting tasks, and updating the completion status of tasks.
The updateCounters() function updates the number of completed and uncompleted tasks.
Event listeners are added to the task elements to handle actions like checking/unchecking the checkbox, editing, and deleting.
