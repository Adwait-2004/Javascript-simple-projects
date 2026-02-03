# Todo App

A minimal and fast Todo application built using HTML, CSS, and vanilla JavaScript. It lets you add tasks, mark them as completed, and delete them. All todos are stored in the browser using LocalStorage, so your list stays even after refreshing the page.

---

## Features

* Add new todo items
* Mark todos as completed using a checkbox
* Delete individual todos
* Todos persist using browser LocalStorage
* Clean dark UI with custom styled checkboxes
* Fully responsive layout

---

## Project Structure

```
├── index.html   # App structure and layout
├── style.css    # Styling and responsive design
├── app.js       # Todo logic and LocalStorage handling
└── README.md
```

---

## How the App Works

### 1. Data Storage

* Todos are stored in `localStorage` under the key `todos`
* Each todo is an object with:

  * `text` – the todo content
  * `completed` – true or false

---

### 2. Adding a Todo

* Type a task in the input field
* Press **Enter** or click **ADD**
* The todo is added to the list and saved instantly

---

### 3. Completing a Todo

* Click the circular checkbox
* The task gets a line-through style
* Completion state is saved automatically

---

### 4. Deleting a Todo

* Click the delete (trash) icon
* The todo is removed from both UI and LocalStorage

---

## JavaScript Overview

* `addTodo()` – creates and saves a new todo
* `updateTodoList()` – re-renders the todo list
* `createTodoItem()` – builds each todo DOM element
* `deleteTodoItem()` – removes a todo
* `saveTodos()` / `getTodos()` – handles LocalStorage

---

## Technologies Used

* HTML5
* CSS3 (custom properties, responsive design)
* Vanilla JavaScript (DOM manipulation, LocalStorage)

---

## How to Run

1. Download or clone the project
2. Open `index.html` in any modern browser
3. Start managing your todos

No setup, no dependencies.

---

## Browser Support

* Works on all modern browsers
* Mobile responsive

---

## Possible Improvements

* Edit existing todos
* Filter (All / Completed / Active)
* Clear completed tasks
* Drag and drop reordering
* Sync with backend

---

## Author

Adwait Pote

---

Simple, focused, and practical todo app.
