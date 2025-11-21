Project Title:- To-Do List Task Manager  


Overview of the Project :-


Hello! This is a simple To-Do List application designed as a Python desktop utility. The project is contained in a single Python file and aims to provide a clean graphical user interface for managing your daily tasks.  
I used the Object-Oriented Programming (OOP) method to develop this application. The main logic for handling tasks—adding, deleting, and updating—was completely separated from the user interface, which includes buttons and lists. This separation makes it easier to understand and expand the code later. Think of it like having a "Task Manager" object as a background service that interacts with the "Window" object only when it needs to show or change something.  
Currently, tasks are stored in temporary memory and will be lost once the application is closed. However, it is easy to add features for permanent storage in the future!  


Features :-


This application simulates the entire process users need to manage their tasks:  

1. Task Creation: There is an input field and an "➕ Add Task" button, or you can press {Enter} to quickly add a new task.  

2. Intuitive Display: All tasks are shown in a vertical list that can be scrolled through. Each task has a unique {ID} tag for easy reference and management.  

3. Status Tracking: With the {"🔁 Toggle Status"} button, you can easily mark a task as done or undone. Completed tasks display a {'✅'} icon next to them.  

4. Editing: The {"✏️ Edit Description"} button opens a small dialog box that lets you quickly fix mistakes or update tasks without re-entering everything.  

5. Deletion: Use the {"🗑️ Delete Task"} button to permanently delete a task.  

6. Error Handling: There are safety checks in place, so you cannot add an empty task.

   

Technologies/Tools Used :-


The project uses a basic, common Python setup that requires no special dependencies to install.  

1. Primary Language: Python 3.x  

2. GUI Framework: Tkinter, which is Python's standard library for building desktop applications.  

3. Libraries: Additional features rely on Python's standard library modules, such as tkinter.messagebox and tkinter.simpledialog.  


Steps to Install & Run the Project :-


Since this project only uses Python's standard library, installation is quick and easy!  

Prerequisites  
Make sure Python 3.x is installed on your machine (version 3.6 or higher is recommended).  

Get the Code  
Clone this repository or download the file containing the source code (to do list.py, assuming you saved the code in a single file).  

Launch the Program  
Open the command prompt (TERMINAL).  

Change to the directory where the Python file is stored.  

Run the script using the Python interpreter (IDLE):  

python to do list.py  
The To-Do List window will appear right after execution.  


Instructions for Testing :-


To ensure everything works correctly, manually perform the following test scenarios.  

| Test Case          | Steps to Execute                                                        | Expected Outcome                               |  
|--------------------|------------------------------------------------------------------------|------------------------------------------------|  
| 1. Add a Task      | Enter "Finish README" in the input box and hit {Enter} (or click 'Add Task'). | The task appears in the list with an ID assigned and no '✅'. |  
| 2. Toggle Status    | Click on the task you just created. Press the {"🔁 Toggle Status"} button. | The task now shows a '✅' icon, confirming it is completed. |  
| 3. Edit a Task      | Select a task and click {"✏️ Edit Description"}. Enter new text and click OK. | The list updates instantly with the new description. |  
| 4. Delete a Task    | Select any task. Click {"🗑️ Delete Task"}.                             | The selected task disappears from the list.   |  
| 5. Input Validation  | Click the {"➕ Add Task"} button while the input box is empty.          | A message box pops up, and no new task is added. |  
| 6. No Selection Error| Ensure no task is highlighted. Click the {"🗑️ Delete Task"} button.     | A message box pops up, asking you to select a task first. |
