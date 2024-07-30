# To-Do List App

This To-Do List app is an intuitive web application built using HTML, CSS, and JavaScript. It allows users to add, edit, and delete tasks, helping them manage their daily activities efficiently.

## Features

- Add new tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as completed
- Responsive design

## Setup

1. **Clone the repository:**

```bash
git clone https://github.com/s-satyajit/todo-list-app-js.git 
cd todo-list-app
```

2. **Open ```index.html``` in your browser**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Todo App</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="stats-container">
            <div class="details">
                <h1>Todo App</h1>
                <p>Keep it up!</p>
                <div id="progress-bar">
                    <div id="progress"></div>
                </div>
            </div>
            <div class="stats-number">
                <p id="numbers"> 0 / 0 </p>
            </div>
        </div>
        <form action="">
            <input type="text" id="taskInput" placeholder="Write your task">
            <button id="newTask" type="submit">+</button>
        </form>
        <ul id="task-list"></ul>

    </div>
    <script src="script.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@tsparticles/confetti@3.0.3/tsparticles.confetti.bundle.min.js"></script>
</body>
</html>
```

3. **Start managing your tasks!**

