📝 To-Do List Web App
A simple, interactive, and persistent to-do list built with HTML, CSS, and vanilla JavaScript. Tasks are saved using localStorage, ensuring that your list is available even after refreshing or reopening the browser.

🔍 Features
    ✅ Add new tasks
    🔄 Mark tasks as completed (with a visual strike-through)
    🗑️ Delete tasks
    💾 Save tasks to browser storage (localStorage)
    ♻️ Persist tasks even after page reloads

🛠️ Technologies Used
    HTML5 – Structure of the app
    CSS3 – Styling (add your custom styles for appearance)
    JavaScript (ES6) – Functionality and logic
    Font Awesome – Icons (trash/delete icon)

📦 How It Works
    1. Load Existing Tasks
    On page load, tasks are fetched from localStorage.
    If there are no tasks, an empty list is initialized.
    
    2. Add New Task
    User enters text in the input field and clicks "Add".
    The task is added to the list with a checkbox and delete icon.
    Tasks are assigned unique IDs for tracking.
    
    3. Toggle Task Completion
    Clicking the checkbox toggles the isChecked status.
    UI is updated to reflect completed tasks with a strike-through style.
    
    4. Delete Task
    Clicking the trash icon removes the task from the UI and todoList.
    
    5. Save Tasks
    Clicking the "Save" button saves the current task list to localStorage.
    📄 Code Overview
    🔧 getTodoListFromLocalStorage()
    
    Fetches and parses the task list from localStorage.
    ➕ onAddTodo()
    Handles new task creation and validation.
    
    ✅ onTodoStatusChange()
    Toggles the task’s completed state and updates the visual style.
    
    ❌ onDeleteTodo()
    Removes a task from the DOM and updates the todoList.

🖼️ UI Preview
simpletodoapps.ccbp.tech

🧱 createAndAppendTodo(todo)

Dynamically creates and appends DOM elements for each task.
