# Task Manager (Bash Script)

A simple task management application built using Bash scripting and standard Linux utilities.

## 📌 Features

- ✅ Create a new task
- 📋 List all tasks
- ✅ Mark tasks as completed
- ❌ Delete a task
- 🔍 Search tasks by keyword
- 📅 Sort tasks by due date
- 📤 Export tasks to a file
- ⏰ Schedule task reminders using `cron`

## 🧰 Technologies Used

- **Bash**
- **Linux CLI Tools**: `echo`, `cat`, `awk`, `sed`, `sort`, `grep`
- **cron**: for task reminders

## 📁 Project Structure

```
task-manager/
├── task_manager.sh       # Main task manager script
├── sample.sh             # Example usage or helper script
├── tasks.txt             # Task database
├── .gitignore            # Ignore temporary files
└── README.md             # This file
```

## ▶️ How to Use

### 1. Make the main script executable:

```bash
chmod +x task_manager.sh
```

### 2. Run the script:

```bash
./task_manager.sh
```

### 3. Example Commands

```bash
./task_manager.sh add "Submit homework" 2025-07-05
./task_manager.sh list
./task_manager.sh done 2
./task_manager.sh delete 3
./task_manager.sh search "homework"
./task_manager.sh sort
./task_manager.sh export
```

> 📝 Tasks are stored in `tasks.txt`  
> ⏰ You can use `cron` to trigger reminders by calling the script with upcoming tasks

## 🐙 GitHub Repository

[https://github.com/mohhassnin/linux-devops-new](https://github.com/mohhassnin/linux-devops-new)

---

## 📄 License

This project is for educational purposes and is not under any specific license.
