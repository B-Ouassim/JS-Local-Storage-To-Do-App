# 📝 Local Storage To-Do List App

A simple yet essential utility application for managing daily tasks. This project is a foundational showcase of client-side web development skills, emphasizing persistence using the browser's built-in storage capabilities.

## ✨ Key Features
* **Task Management:** Users can add new tasks to the list.
* **Persistent Data:** Tasks are saved locally using **`localStorage`**, meaning the list persists even after the user closes and re-opens the browser.
* **Check/Uncheck:** Tasks can be marked as complete by clicking on them.
* **Deletion:** A simple 'x' button allows users to remove tasks from the list permanently.
* **Responsive UI:** Clean, modern design built with CSS for a pleasant user experience on any device.

## 💻 Technologies Used
* **HTML5:** Structured the To-Do container and input form.
* **CSS3:** Styled the application, including the check/uncheck visual states.
* **JavaScript (Vanilla):** Handled all core logic:
    * **DOM Manipulation** (creating `<li>` and `<span>` elements).
    * **Event Listeners** (for adding tasks and handling clicks).
    * **Local Storage API** (`localStorage.setItem()` and `localStorage.getItem()`) for saving data.

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/JS-Local-Storage-To-Do-App.git](https://github.com/YourUsername/JS-Local-Storage-To-Do-App.git)
    ```
2.  **Launch:** Open the `index.html` file in your web browser. No server is required.

## 💡 How it Works
When you add a task, click it to mark it complete, or click the 'x' to remove it, the JavaScript immediately calls the `saveData()` function. This function saves the entire contents of the list to the browser's Local Storage, ensuring your tasks are still there the next time you visit the page.
