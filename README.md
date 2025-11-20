# Project Title: To-Do List Task Manager

# Overview of the Project

Hi there! This is a simple, straightforward (To-Do List application) built as a Python desktop utility. The entire project is housed in a single Python file, designed to give you a clean, graphical interface for managing your daily tasks.

I developed this application using clear (Object-Oriented Programming (OOP)) principles. The goal was to keep the core logic (handling the tasks—adding, deleting, updating) completely separate from the user interface (the buttons and lists). This separation makes the code easy to maintain and expand later on. Think of it as having a dedicated "Task Manager" object running quietly in the background, only communicating with the "Window" object when it needs to show or change something.

Right now, the tasks are stored (in memory) (they disappear when you close the app), but it's built to be easily upgraded for persistent storage later on!

---

# Features

The application provides a full set of management tools necessary to handle your tasks efficiently:

1- Task Creation: Quickly add a new task using the input field and the ("➕ Add Task") button (or just press {Enter}).
2- Intuitive Display:** View all tasks in a scrollable list, each labeled with a unique {ID} for easy reference and management.
3- Status Tracking: Easily toggle a task as complete or incomplete using the {"🔁 Toggle Status"} button. Completed tasks are marked with a {'✅'} icon.
4- Editing: Click {"✏️ Edit Description"} to pop up a small dialog box, letting you quickly correct typos or update details without re-entering the entire task.
5- Deletion:** Permanently remove tasks with the {"🗑️ Delete Task"} button.
6- Error Handling: Built-in checks prevent you from adding blank tasks or attempting to modify/delete tasks when nothing is selected, guiding the user with simple warning messages.

---

# Technologies/Tools Used

This project uses a minimal, standard Python setup, meaning there are no complex third-party dependencies to install!

1- Core Language: (Python 3.x)
2- GUI Framework: (Tkinter) (Python’s built-in standard library for creating desktop applications).
3- Libraries: All other functionality relies on standard Python library components (`tkinter.messagebox`, `tkinter.simpledialog`, etc.).



# Steps to Install & Run the Project

Since this project relies only on Python's standard library, setup is quick and easy!

1. Prerequisites

You must have (Python 3.x) installed on your system (version 3.6 or newer is ideal).

 2. Download the Code

1.  Clone this repository or download the source code file (`to do list.py`, assuming you saved the code in a single file).

3. Run the Application

1.  Open your command line interface (Terminal, PowerShell, etc.).
2.  Navigate to the directory where you saved the Python file.
3.  Execute the script using the Python interpreter:

    ```bash
    python to do list.py
    ```

4.  The To-Do List window should pop up instantly!



# Instructions for Testing

To ensure the application is running correctly, manually test the following core scenarios.

| Test Case | Steps to Execute | Expected Outcome |

1- Add a Task:-  Type "Finish README" into the input box and press {Enter} (or click the 'Add Task' button).  The task appears immediately in the list below with a unique ID and no '✅'. 
2- Toggle Status:-  Select the task you just added. Click the {"🔁 Toggle Status"} button. The task entry should now show the {'✅'} icon, indicating completion. 
3- Edit a Task:-  Select a task. Click {"✏️ Edit Description"}. Change the text and click OK. The listbox entry updates instantly with the new description.
4- Delete a Task:-  Select any task. Click {"🗑️ Delete Task"}. The selected task disappears completely from the list. 
5- Input Validation:-  Click the {"➕ Add Task"} button while the input box is completely empty.  
[Warning]:- A message box pops up, and no new task is added.
7- No Selection Error:-  Ensure no task is highlighted. Click the {"🗑️ Delete Task"} button.  [Warning]:- A message box pops up, asking you to select a task first. 


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
