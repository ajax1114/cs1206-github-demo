# 📌 Smart Task Scheduler with Priority Management System

## 📖 Description

The Smart Task Scheduler with Priority Management System is designed to provide an efficient and structured way of managing tasks, deadlines, and priorities. By utilizing fundamental data structures, the system categorizes and arranges tasks based on their level of urgency and importance.

Through this approach, users are guided to focus on high-priority tasks first while still keeping track of regular activities. The system ultimately aims to improve productivity, enhance time management skills, and reduce the risk of missed deadlines.

---

## 👥 Collaborators

**Group 3**

<table align="center">
  <tr>
    <th>Photo</th>
    <th>SR-Code</th>
    <th>Name</th>
    <th>Duties/Responsibilities</th>
  </tr>

  <tr align="center">
    <td>
      <img src="dhymple.jpg" width="120px">
    </td>
    <td>25-04128</td>
    <td>Carandang, Dhymple Norshe F.</td>
    <td>Documenter, Main Programmer, System Architect</td>
  </tr>

  <tr align="center">
    <td>
      <img src="minerva.jpg" width="120px">
    </td>
    <td>25-09305</td>
    <td>Rabi, Minerva R.</td>
    <td>Documenter, Main Programmer, System Architect</td>
  </tr>
</table>
---

## ❗ Problem

Students often struggle to manage multiple academic tasks, deadlines, and priorities effectively. With overlapping requirements and limited time, it becomes difficult to stay organized and focused. As a result, many students experience:

Missed or late submissions
Inefficient use of time
Disorganized and overwhelming workloads

These challenges highlight the need for a system that can intelligently organize tasks based on urgency and importance, helping users prioritize what matters most.

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

📝 Closing Statement

The Smart Task Scheduler with Priority Management System demonstrates how fundamental data structures—such as stacks, queues, and priority queues—can be applied to solve real-world problems. This project provides a practical solution for improving task organization, time management, and productivity.
