# Student Course Enrollment System (TypeScript)

A console-based Student Course Enrollment System built using **TypeScript** and **Object-Oriented Programming (OOP)** principles. This application runs entirely in the terminal with an interactive CLI.

## 🚀 Features

-   **Entities**: Students, Instructors, Courses, and Enrollments.
-   **Interactive CLI**: Easy-to-use menu to manage the system.
-   **CRUD Operations**: Create, Read, Update (simulated), and Delete (simulated) for Students and Courses.
-   **Advanced Logic**:
    -   Enrollment capacity checks.
    -   Duplicate enrollment prevention.
    -   Search Students by name.
    -   Filter Courses by level.
    -   Sort Courses by credits.
-   **In-Memory Storage**: Data persists while the application is running.

## 🛠️ Prerequisites

-   [Node.js](https://nodejs.org/) (v14 or higher)
-   npm (Node Package Manager)

## 📦 Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/AyushCodes160/Student-Course-Enrollement-System-TypeScript.git
    cd Student-Course-Enrollement-System-TypeScript
    ```

2.  Install dependencies:
    ```bash
    npm install
    ```

## 🎮 How to Use

1.  **Start the Application**:
    ```bash
    npm start
    ```

2.  **Interact with the Menu**:
    You will see the following options:
    ```text
    1. Add Student
    2. List Students
    3. Add Course
    4. List Courses
    5. Enroll Student
    6. Exit
    ```

3.  **Examples**:
    -   **Add a Student**: Select `1`, then enter the Name and Email.
    -   **Add a Course**: Select `3`, enter Title, Description, and Credits.
    -   **Enroll**: Select `5`, you will need the `Student ID` (from option 2) and `Course ID` (from option 4).

## 📂 Project Structure

```bash
src/
├── models/         # Data models (Student, Course, User, etc.)
├── services/       # Business logic (Enrollment rules, Search, etc.)
└── index.ts        # Main entry point and CLI logic
```

## 📝 Tech Stack

-   **Language**: TypeScript
-   **Runtime**: Node.js (via `ts-node`)
-   **Architecture**: Layered (Models -> Services -> UI)
