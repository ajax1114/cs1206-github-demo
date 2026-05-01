# 📌 Smart Task Scheduler with Priority Management System

## 📖 Description

This project is developed for **CC 103 - Data Structures and Algorithms** under the Computer Science Department (2nd Semester, AY 2025–2026).

The **Smart Task Scheduler with Priority Management System** helps users efficiently manage tasks, deadlines, and priorities. It organizes tasks based on urgency and importance, improving productivity and reducing missed deadlines.

---

## 👥 Collaborators

**Group 3**

| SR-Code  | Name                         | Duties/Responsibilities                       |
| -------- | ---------------------------- | --------------------------------------------- |
| 25-04128 | Carandang, Dhymple Norshe F. | Documenter, Main Programmer, System Architect |
| 25-09305 | Rabi, Minerva R.             | Documenter, Main Programmer, System Architect |

---

## ❗ Problem

Students often struggle to manage multiple tasks, deadlines, and priorities efficiently, which leads to:

* Missed deadlines
* Poor time management
* Disorganized workload

A system is needed to organize tasks based on urgency and importance.

---

## 🧠 Data Structures Used

### 🔹 Stack

* **Purpose:** Undo the last action (e.g., delete or edit a task)
* **Reason:** Uses LIFO (Last In, First Out) to reverse recent actions

### 🔹 Queue

* **Purpose:** Manage normal tasks in order of entry
* **Reason:** Uses FIFO (First In, First Out) for fair processing

### 🔹 Priority Queue

* **Purpose:** Handle urgent or high-priority tasks
* **Reason:** Ensures important tasks are processed first

---

## ✨ Key Features

* ➕ Add, edit, and delete tasks
* 🔺 Assign priority levels (Low, Medium, High)
* 📊 Automatically sort tasks based on deadline and priority
* ↩️ Undo last action
* 📅 Display daily workload
* ✅ Mark tasks as completed
* 📋 View all tasks and track their status

---

## ⚙️ How the System Works

1. **Main Menu**

   * Add Task
   * View Tasks
   * Undo Last Action
   * Exit

2. **Add Task**

   * User inputs task name, deadline, and priority
   * System validates input
   * Normal tasks → added to Queue
   * Urgent tasks → added to Priority Queue
   * Action stored in Stack for undo

3. **View Tasks**

   * Displays priority tasks first
   * Then displays normal tasks

4. **Undo Last Action**

   * Checks if the stack is empty
   * If not, reverses the most recent action