# Modern Todo App

A lightweight, responsive, and persistent Task Management application built with vanilla HTML, CSS, and JavaScript. This project features a modern UI with gradient aesthetics and robust state management using local storage.

## 🚀 Features

* **CRUD Functionality:** Create, Read, Update, and Delete tasks seamlessly.
* **Data Persistence:** Uses `localStorage` to save your tasks, ensuring data is not lost on page refreshes.
* **Real-time Statistics:** Dashboard displays live counts for Total, Active, and Completed tasks.
* **Responsive Design:** Adapts fluidly from mobile views (vertical list) to desktop views (grid layout).
* **Task Editing:** Includes a modal interface for modifying existing tasks.
* **Modern UI/UX:** Features hover effects, smooth transitions, and a clean, card-based layout.

## 🛠️ Tech Stack

* **HTML5:** Semantic markup for structure.
* **CSS3:** Flexbox, CSS Grid, and Media Queries for layout and styling.
* **JavaScript (ES6+):** Vanilla JS for DOM manipulation and logic (no external libraries).

## 📦 How to Run

Since this is a single-file application, no build process or package manager is required.

1.  Download or create a file named `index.html`.
2.  Paste the source code into the file.
3.  Open `index.html` in any modern web browser (Google Chrome, Firefox, Safari, etc.).

## 📂 Code Overview

The logic is encapsulated within the `<script>` tag handling the following key functions:

* **State Management:** The `tasks` array holds the application state.
* **`loadTasks()`:** Initializes the app by retrieving JSON data from local storage.
* **`render()`:** Dynamically regenerates the HTML for the task list based on the current state.
* **`save()`:** Serializes the task array and saves it to the browser's storage.

## 🔮 Future Improvements

* Add drag-and-drop functionality for reordering tasks.
* Implement categories or tags for tasks.
* Add Dark Mode toggle.

---

**Author:** Akanshu Jamwal
