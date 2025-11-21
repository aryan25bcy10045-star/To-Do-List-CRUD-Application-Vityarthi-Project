# Project Title:  To-Do List Task Manager


# Overview of the Project

Hello! This is a very simple and basic (To-Do List application) made as a Python desktop utility. The whole project is contained in one single Python file and it aims to provide you with a neat and graphical user interface for the administration of your daily chores.

I used the clean (Object-Oriented Programming (OOP)) method when developing this application. The core logic (dealing with the tasks—adding, deleting, updating) was completely separated from the user interface (the buttons and lists) which was the goal. This division eases the underground and later on expansion of the code. Imagine it like you have a "Task Manager" object as a background service that only interacts with the "Window" object if it needs to display something or change it.

Currently, the tasks are kept (in temporary memory) (they are lost once the application is closed) but it is made easy to add the necessary features for persistent storage in the future!

# Features

This application mocks up the entire process that the users would require to manage the their tasks:

1- Task Creation: There is an input field and an ("➕ Add Task") button (or just press {Enter}) to quickly add a new task.

2- Intuitive Display:** All the tasks are displayed in a vertical list that can be scrolled through and where each task has been given its unique {ID} tag for easy reference and management.

3- Status Tracking: Using the {"🔁 Toggle Status"} button you can very easily mark a task as done or undone. The completed tasks have a {'✅'} icon next to them.

4- Editing: With the help of the {"✏️ Edit Description"} you can get a small dialog box that will allow you to quickly fix any mistakes or give updates without having to re-enter the entire task.

5- Deletion:** Using the {"🗑️ Delete Task"} button you can make the task deleted permanently.

6- Error Handling: Safety checks are in place so that you will not be able to add an empty task or try




# Technologies/Tools Used


The project brings along a basic, common Python configuration which makes the installation of dependencies not being a problem at all, since there are none!


1- Primary Language: (Python 3.x)

2- GUI Framework: (Tkinter) (Python's standard library for building desktop applications).

3- Libraries: The remaining features depend on Python's standard library modules (`tkinter.messagebox`, `tkinter.simpledialog`, etc.).



# Steps to Install & Run the Project

As this project is based only in Python's standard library, the installation is fast and simple!

1. Prerequisites

Ensure that (Python 3.x) is installed on your machine (the recommended version is 3.6 or higher).

2. Get the Code

1. Clone this repository or download the file containing the source code (`to do list.py`, assuming you stored the code in one single file).

3. Launch the Program 

1. Open command prompt {TERMINAL}. 
2. Change the location of directory where the Python file is stored. 
3. Run the script using the Python interpreter: (IDLE) 

    ```bash
    python to do list.py
    ```

4. The To-Do List window will appear immediately after execution



# Instructions for Testing

To verify that everything is working as they should, perform the following tests scenarios manually.

| Test Case | Steps to Execute | Expected Outcome |

1- Add a Task:-  Enter "Finish README" in the input box and hit {Enter} (or mouseclick 'Add Task' button).  The task comes up instantly in the lower list with an ID assigned and no '✅'.

2- Toggle Status:-  Click on the task you just made. Press the {"🔁 Toggle Status"} button. The task now would be having '✅' icon, confirming that it is completed.

3- Edit a Task:-  Select a task and click {"✏️ Edit Description"}. Enter the new text and click OK. The list will shows instantly with the new description updated.

4- Delete a Task:-  Select any task. Click {"🗑️ Delete Task"}. The selected task disappears completely from the list. 

5- Input Validation:-  Click the {"➕ Add Task"} button while the input box is completely empty it will add task.  
[Warning]:- A message box pops up, and no new task is added again the program is run.

6- No Selection Error:-  Ensure no task is highlighted. Click the {"🗑️ Delete Task"} button.  [Warning]:- A message box pops up, asking you to select a task first. 


# Screenshots

@MAIN INTERFACE

<img width="1470" height="403" alt="MAIN INTERFACE" src="https://github.com/user-attachments/assets/a08755c4-264f-4743-9401-de7e02be1b24" />

@INTERFACE AFTER ADDING TASK

<img width="527" height="429" alt="INTERFACE AFTER ADDING TASK" src="https://github.com/user-attachments/assets/55e0e2a7-1c0a-4447-9ce8-a7b6b34a820e" />

@INTERFACE AFTER CHANGING STATUS OF TASK

<img width="518" height="406" alt="INTERFACE AFTER CHANGING STATUS OF TASK" src="https://github.com/user-attachments/assets/60980b68-7872-4796-a5af-08559c271938" />

@INTERFACE WHILE EDITING DESCRIPTION

<img width="750" height="519" alt="INTERFACE WHILE EDITING DESCRIPTION" src="https://github.com/user-attachments/assets/2dc247b3-0ebe-4362-9520-f0f0d3c44d25" />

@INTERFACE WHILE DELETING TASK

<img width="521" height="407" alt="INTERFACE WHILE DELETING TASK" src="https://github.com/user-attachments/assets/e99b4589-726e-450f-a1e9-54df7723d080" />

@INTERFACE WHILE ADDING TASK

<img width="573" height="446" alt="INTERFACE WHILE ADDING TASK" src="https://github.com/user-attachments/assets/8e2e0b0b-5cca-40b0-8ac8-a8f03d88abf1" />
