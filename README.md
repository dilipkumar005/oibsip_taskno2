# To-Do App

A simple Android To-Do application that allows users to manage their tasks efficiently. This app uses SQLite for local data storage and implements a clean user interface with Material Design components.

## Features

- Add new tasks : Users can add new tasks using a Floating Action Button (FAB).
- View all tasks in a list
- Delete tasks with swipe-to-delete functionality
- Swipe to Delete: Swipe left or right on a task to delete it from the list.
- Simple and intuitive user interface
- Data persistence using SQLite
- Simple UI: A clean, user-friendly interface using Android's Material Design components.
- Persist Data: All tasks are stored in a local SQLite database, so they persist between app sessions.


## Technologies Used

- Android Studio : The core Android development tools and libraries.
- Java : Programming language used for app development.
- SQLite : Local database for storing and retrieving tasks.
- RecyclerView : A flexible view for providing a limited window of data and dynamically loading views.
- Material Design Components : For modern, responsive UI elements (e.g., FloatingActionButton).
- ItemTouchHelper: For implementing swipe gestures in RecyclerView to delete tasks.


## Installation
**Clone the repository:**

git clone https://github.com/dilipkumar005/oibsip_taskno2.git

**Open the project in Android Studio:**

- Open Android Studio and select "Open an existing project."
- Navigate to the directory where you cloned the repository and open the project.

## Run the app:

- Connect an Android device or start an Android emulator.
- Click "Run" (the green play button) in Android Studio.

## Code Overview

**MainActivity.java:** The main activity of the app. It sets up the RecyclerView, Floating Action Button (FAB), and integrates with the database.

**ToDoAdapter.java:** An adapter class for the RecyclerView that binds the task data to the list items.

**ToDoModel.java:** A simple model class representing each task, with fields for the task title, description, and ID.

**DataBaseHelper.java:** A helper class for interacting with the SQLite database. It contains methods for adding, retrieving, and deleting tasks.

**RecyclerViewTouchHelper.java:** A helper class to handle swipe-to-delete gestures on the RecyclerView.


## How to Use
**Add a New Task:**

Tap on the Floating Action Button (FAB) at the bottom-right corner of the screen to open a dialog to add a new task.

**View Tasks:**

After adding tasks, they will appear in a list. Swipe left or right on a task to delete it.

**Swipe to Delete:**

You can delete tasks by swiping them left or right in the list.

**Task Persistence:**

Tasks are saved locally in the SQLite database, so even if you close and reopen the app, your tasks will be retained.


