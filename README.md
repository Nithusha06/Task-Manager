# 📋 Task Manager App

This mobile application is developed using **Kotlin** to help users manage a list of tasks. It follows the **MVVM (Model-View-ViewModel)** architecture pattern and uses **Room** for local data storage with an SQLite database. The app efficiently handles state management with **LiveData** and **ViewModel**.

---

## 🎨 Features

- **User-Friendly Interface**: A clean and intuitive UI using XML layouts, ensuring ease of use when adding, editing, viewing, and deleting tasks.
- **Task Management**:
  - ➕ **Add** new tasks via a form.
  - 👀 **View** tasks in a **RecyclerView**.
  - ✏️ **Edit** and 🗑️ **delete** tasks.
- **Architecture**: 
  - Follows the **MVVM** architecture pattern for clean separation of concerns.
- **Data Storage**:
  - Utilizes **Room** for local data storage in an SQLite database.
  - Implements the **Repository pattern** for abstracted data access.

---

## 🛠️ Technologies Used

- **Kotlin** for app development.
- **Jetpack Components**:
  - **ViewModel**: Handles UI-related data.
  - **LiveData**: For reactive data handling.
  - **Room**: For local database interactions with SQLite.
- **RecyclerView**: Displays the list of tasks.

---

## 🚀 How to Run

1. **Clone the repository** and open the project in Android Studio:
   ```bash
   git clone https://github.com/yourusername/task-manager-app.git

2. Sync the project to download dependencies.
3. Run the app on an Android emulator or physical device.

