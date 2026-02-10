# ✨ Modern Todo App

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

> A lightweight, responsive, and persistent Task Management application featuring a gradient aesthetic and robust local storage integration.



---

## 📑 Table of Contents
- [✨ Modern Todo App](#-modern-todo-app)
  - [📸 Screenshots](#-screenshots)
  - [🚀 Features](#-features)
  - [🛠️ Tech Stack](#-tech-stack)
  - [📦 Installation & Usage](#-installation--usage)
  - [📂 Code Structure](#-code-structure)
  - [🔮 Roadmap](#-roadmap)
  - [👤 Author](#-author)

---

## 🚀 Features

This application goes beyond a basic to-do list by implementing real-world data handling and UI/UX best practices.

| Feature | Description |
| :--- | :--- |
| **💾 Persistent Storage** | Tasks are saved to `localStorage`, so your data survives page reloads. |
| **📊 Real-time Stats** | Live dashboard showing **Total**, **Active**, and **Completed** tasks. |
| **📱 Fully Responsive** | Adapts from a vertical mobile list to a clean desktop grid layout. |
| **✏️ Edit Mode** | Integrated modal interface for quick task updates. |
| **🎨 Modern UI** | Glassmorphism-inspired design with smooth hover effects and transitions. |

---

## 🛠️ Tech Stack

Built with pure vanilla web technologies to demonstrate core understanding of the DOM.

* **Structure:** HTML5 (Semantic)
* **Styling:** CSS3 (Flexbox, Grid, Linear Gradients, Media Queries)
* **Logic:** JavaScript (ES6+, LocalStorage API, Event Delegation)

---

## 📦 Installation & Usage

Since this is a client-side application, no Node.js or package manager is required.

1.  **Clone the repository** (or download the source):
    ```bash
    git clone [https://github.com/yourusername/modern-todo-app.git](https://github.com/yourusername/modern-todo-app.git)
    ```
2.  **Navigate to the project folder:**
    ```bash
    cd modern-todo-app
    ```
3.  **Launch:**
    Simply open the `index.html` file in any modern browser (Chrome, Firefox, Safari).

---

## 📂 Code Structure

The logic is encapsulated within a single file for portability, focusing on these key functions:

* `loadTasks()`: 📥 **Hydration** - Reads JSON data from browser storage on boot.
* `render()`: 🎨 **Paint** - Dynamically generates HTML elements based on state.
* `save()`: 💾 **Persist** - Serializes the state array to JSON strings.
* `toggle(id)` & `deleteTask(id)`: ⚡ **Actions** - State modifiers for user interaction.

---

## 🔮 Roadmap

Future improvements planned for this project:

- [ ] **Drag & Drop:** Implement reordering of tasks.
- [ ] **Categorization:** Add tags or project folders.
- [ ] **Dark Mode:** System-preference aware dark theme.
- [ ] **PWA Support:** Make it installable on mobile devices.

---

## 👤 Author

**Akanshu Jamwal**

* **Github:** [@akanshujamwal](https://github.com/akanshujamwal)
* **LinkedIn:** [Akanshu Jamwal](https://www.linkedin.com/in/akanshu-jamwal)

---

<div align="center">
  <sub>Built with ❤️ using React JS</sub>
</div>
