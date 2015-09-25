# taskManager
todo list for multiple users with Angular.js

This project stared as a simple todo app with Angular, like my backbone calendarApp.  The user is a manager of employees and regularly has a different set of tasks to complete, but has a hard time tracking who is doing those tasks and when or if they are completed.  With this app, the user can first create their list of tasks to complete, clock in employees as they arrive for work, and assign those employees tasks from the main list.  When the employee reports completion of a task, the task is moved off of the employee list and into the completion list with the employee's name and time of completion.  Server side code is very basic and was only added at the end.  Angular side has one controller and has a filter on the date object.  Several conditional statements were added into the $scope methods for testing purposes.