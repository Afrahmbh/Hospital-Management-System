# 🏥 HealZone Hospital Management System

> **A C++ Data Structures project that simulates a connected hospital workflow using Linked Lists, Queues, Stacks, and Priority Queues.**

## 📌 Overview

**HealZone Hospital Management System** is a console-based C++ application designed to demonstrate how fundamental **data structures** can be applied to a real-world hospital environment.

The system manages patients through different stages of care, including patient records, emergency room processing, treatment tracking, and critical patient prioritization.

---

## ✨ Key Features

* 👤 **Patient Records**

  * Add and store patient information
  * Search patients by ID
  * Display registered patients

* 🚑 **Emergency Room Management**

  * Admit patients into the ER
  * Process patients using **FIFO** order
  * Display the ER queue

* 🩺 **Treatment Management**

  * Record completed treatments
  * Undo the most recent treatment using **LIFO** behavior

* 🚨 **Critical Patient Prioritization**

  * Assign criticality levels
  * Organize patients according to priority
  * Display critical patients by priority level

* 🖥️ **Interactive Console**

  * Menu-driven interface
  * Input validation
  * Connected data structure operations

---

## 🧠 Data Structures Used

| Data Structure       | Purpose                                    |
| -------------------- | ------------------------------------------ |
| 🔗 **Linked List**   | Stores and searches patient records        |
| 🚑 **Queue**         | Manages Emergency Room patients using FIFO |
| 📚 **Stack**         | Stores treatment logs and supports undo    |
| ⚡ **Priority Queue** | Organizes critical patients by priority    |

---

## 🔄 System Workflow

```text
              ┌─────────────────────┐
              │   Patient Records   │
              │    Linked List      │
              └──────────┬──────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │   Emergency Room    │
              │       Queue         │
              └──────────┬──────────┘
                    ┌────┴────┐
                    ▼         ▼
          ┌──────────────┐  ┌─────────────────┐
          │   Treatment  │  │ Critical Patient│
          │     Stack    │  │ Priority Queue  │
          └──────────────┘  └─────────────────┘
```

---

## 🎯 Main Operations

```text
1. Add Patient
2. Display Patients List
3. Admit Linked List Patient to ER
4. Display ER Queue
5. Treat Next Patient in ER
6. Log Treatment for ER Front
7. Move ER Front to Critical Queue
8. Display Critical Patients
9. Undo Last Treatment
0. Exit
```


## 📂 Project Structure


| File/Folder              | Description                                      |
|--------------------------|--------------------------------------------------|
| `hospitalcode.cpp`       | Main logic for the system (C++ with file handling) |
| `hospitalcode.cgi`       | Compiled CGI binary for web submission handling  |
| `hospitalinterface.html` | Web interface with form navigation               |
| `hospitalLogo.png`       | Hospital branding/logo used in header            |
| `patients.txt`           | Stores patient record submissions                |
| `emergency.txt`          | Stores emergency room queue data                 |
| `treatments.txt`         | Stores treatment record submissions              |
| `output/`                | Optional: compiled output (e.g., `.exe`, `.cgi`) |
| `README.md`              | Project overview and usage instructions          |

---

## 🎓 Project Objective

The main objective of **HealZone** is to demonstrate the practical use of multiple data structures within a single connected system.

By combining **Linked Lists, Queues, Stacks, and Priority Queues**, the project models different aspects of hospital patient management while reinforcing fundamental **Data Structures and Algorithms** concepts.

---

### 👩‍💻 Team 

* **Authors:** Afrah Bashaddadah, Afnan Kamel, Aya Mohammed, Jana Mufti
* **Supervisor:** Dr. Naila Marir


