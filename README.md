# ✅ To-Do List App

## 📌 Overview
This is a **To-Do List App** built with **Kotlin** that helps users manage their daily tasks efficiently. It allows users to add, edit, delete, and mark tasks as completed. The app follows **MVVM architecture** and uses **Room Database** for local data storage.

## 🎯 Features
- 🔹 Add, Edit, Delete Tasks
- 🔹 Mark Tasks as Completed or Pending
- 🔹 Persistent Storage with Room Database
- 🔹 User-Friendly UI with Material Design
- 🔹 Dark Mode Support 🌙
- 🔹 Notifications & Reminders (Upcoming)

## 🛠 Tech Stack
- **Language:** Kotlin
- **UI Framework:** XML / Jetpack Compose
- **Architecture:** MVVM (Model-View-ViewModel)
- **Local Database:** Room Database
- **Dependency Injection:** Hilt (Optional)

## 🔧 Setup & Installation
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/todo-list-app.git
   ```
2. **Open in Android Studio**
3. **Sync Gradle & Run the App**
   ```bash
   gradle sync
   ```

## 📝 Usage Example (Kotlin - Room Database)
```kotlin
@Entity(tableName = "tasks")
data class Task(
    @PrimaryKey(autoGenerate = true) val id: Int = 0,
    val title: String,
    val isCompleted: Boolean = false
)
```

## 📸 Screenshots
![Task List](https://via.placeholder.com/400x800)
![Task Details](https://via.placeholder.com/400x800)

## 🔥 Future Enhancements
- 🔹 Cloud Sync with Firebase 🔥
- 🔹 Task Reminders & Notifications ⏰
- 🔹 Drag & Drop Task Sorting 🎯

## 🤝 Contribution
Contributions are welcome! Feel free to open issues and submit pull requests.

## 📜 License
This project is licensed under the **MIT License**.

🚀 **Start managing your tasks effectively with this To-Do List App!**
