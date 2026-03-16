# ✨ Modern Todo App

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

> A lightweight, responsive, and persistent **Task Management Application** built using pure **HTML, CSS, and JavaScript**, featuring a modern UI and browser storage integration.

---

# 📑 Table of Contents

- [✨ Modern Todo App](#-modern-todo-app)
  - [📌 Features](#-features)
  - [🛠 Tech Stack](#-tech-stack)
  - [🚀 Installation & Usage](#-installation--usage)
  - [📂 Code Structure](#-code-structure)
  - [📊 Core Functionality](#-core-functionality)
  - [🗺 Roadmap](#-roadmap)
  - [👨‍💻 Author](#-author)

---

# 📌 Features

This application implements practical **frontend engineering concepts** and **UI/UX best practices**.

| Feature | Description |
| :--- | :--- |
| 💾 Persistent Storage | Tasks are stored in `localStorage` so they remain saved after refresh. |
| 📊 Real-time Statistics | Displays **Total Tasks**, **Active Tasks**, and **Completed Tasks**. |
| 📱 Fully Responsive | Mobile-first layout that transforms into a grid on larger screens. |
| ✏️ Edit Tasks | Edit tasks through a clean modal interface. |
| 🗑 Delete Tasks | Remove tasks instantly with a delete button. |
| ✔️ Task Completion | Mark tasks as completed using checkboxes. |
| 🎨 Modern UI | Gradient backgrounds, card layout, and hover animations. |

---

# 🛠 Tech Stack

Built using **vanilla web technologies** to demonstrate a strong understanding of the DOM and browser APIs.

| Technology | Purpose |
|------------|--------|
| **HTML5** | Structure and layout |
| **CSS3** | Styling, responsive design, animations |
| **JavaScript (ES6+)** | Application logic |
| **LocalStorage API** | Data persistence |

---

# 🚀 Installation & Usage

This is a **client-side application**, so no build tools or dependencies are required.

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/modern-todo-app.git
```

### 2️⃣ Navigate to the project folder

```bash
cd modern-todo-app
```

### 3️⃣ Launch the app

Simply open:

```
index.html
```

in any modern browser such as **Chrome, Firefox, or Safari**.

---

# 📂 Code Structure

The project is intentionally simple and contained in a single file.

```
modern-todo-app
│
├── index.html
│
└── README.md
```

### index.html includes:

- HTML layout
- CSS styling
- JavaScript logic

This makes the application **easy to understand and portable**.

---

# 📊 Core Functionality

The application works around a **task state array** that stores tasks and syncs them with LocalStorage.

### Task Object Structure

```javascript
{
  id: 16928373636,
  text: "Complete project documentation",
  completed: false
}
```

---

### Key Functions

#### `loadTasks()`

Loads saved tasks from LocalStorage when the application starts.

#### `render()`

Dynamically generates task cards and updates the UI.

#### `save()`

Stores the task array inside LocalStorage.

```javascript
localStorage.setItem("tasks", JSON.stringify(tasks));
```

#### `toggle(id)`

Marks tasks as completed or active.

#### `deleteTask(id)`

Removes a task from the list.

#### `editTask(id)`

Opens the modal and allows editing the task text.

---

# 🗺 Roadmap

Future improvements planned for this project:

- [ ] Drag & Drop task ordering
- [ ] Task categories or tags
- [ ] Dark mode support
- [ ] Task search functionality
- [ ] Task filtering (All / Active / Completed)
- [ ] Due dates and reminders
- [ ] Progressive Web App (PWA) support

---

# 👨‍💻 Author

**Akanshu Jamwal**

Flutter Developer | Software Engineer | Tech Enthusiast

GitHub  
https://github.com/akanshujamwal

LinkedIn  
https://www.linkedin.com/in/akanshu-jamwal

---

<div align="center">

### ⭐ If you like this project, consider giving it a star!

</div>
