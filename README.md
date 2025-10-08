# Financial Navigator: University Student Financial Management System

[![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)]()
[![Technology](https://img.shields.io/badge/Stack-C%23%20%7C%20MySQL-blue.svg)]()

## 📝 Project Overview

[cite_start]This project is a standalone, client-server financial management application designed to address the significant challenge of **financial illiteracy and budgeting difficulties** faced by university students[cite: 543, 547].

[cite_start]Developed as part of a System Analysis and Design course, the application provides a user-friendly platform for students to gain control over their limited income, track their spending, and plan their finances effectively, ultimately reducing financial stress[cite: 545, 720].

## 💡 Business Problem & Analysis (BA Focus)

[cite_start]The core objective was to develop a tailored solution where existing commercial tools fall short[cite: 574]. [cite_start]The analysis phase focused heavily on understanding the unique financial pain points of the target user base (university students)[cite: 576].

### Key BA Contributions

| Phase | Activity | Documentation & Output |
| :--- | :--- | :--- |
| **Requirements Gathering** | [cite_start]Conducted interviews and surveys to identify core functional needs, such as managing financial aid and setting granular expense categories[cite: 583]. | [cite_start]Developed **Functional Requirements** (FRs) and **Non-Functional Requirements** (NFRs) covering usability, security, and performance[cite: 584, 589]. |
| **Feasibility Assessment** | [cite_start]Executed a comprehensive **Feasibility Study** (Technical, Operational, Economic, and Schedule)[cite: 520]. | [cite_start]Determined a high **Return on Investment (ROI) of 66.67%** and a projected payback period of 7.2 months, justifying the investment in the project[cite: 612]. |
| **System Design** | Modeled the proposed system architecture for development clarity. | [cite_start]Produced detailed **UML Diagrams** (Use Case, Class, and Activity Diagrams) [cite: 805, 846, 864][cite_start], and a **System Requirement Specification (SRS)** document[cite: 733]. |

## ✨ Key Features of the Application

The system is designed around the core needs identified during the requirements analysis, providing the following functionalities:

* [cite_start]**Secure Authentication:** User registration and login with encrypted password storage (using BCrypt)[cite: 751, 802].
* [cite_start]**Income & Expense Tracking:** CRUD (Create, Read, Update, Delete) functionality to log financial transactions, including support for financial aid management[cite: 585, 635, 644].
* [cite_start]**Budgeting & Planning:** Tools to create and monitor personal budgets against actual spending[cite: 551, 585].
* [cite_start]**Visual Data Dashboard:** A dynamic dashboard providing an overview of the user's current financial status[cite: 636, 672].
* [cite_start]**Reports & Analytics:** Generates charts to visualize income and expense breakdowns over selected periods[cite: 587, 755, 775].
* [cite_start]**Reminder System:** Users can set and manage reminders for important financial deadlines or tasks[cite: 636, 647].

## 🛠 Technology Stack

[cite_start]The application utilizes a robust client-server architecture[cite: 793].

* [cite_start]**Frontend (Client):** C# Windows Forms (Standalone Desktop Application) [cite: 556, 800]
* [cite_start]**Backend (Database):** MySQL Database [cite: 556, 801]
* [cite_start]**Development Environment:** Microsoft Visual Studio [cite: 911]
* [cite_start]**Security Libraries:** BCrypt (for password hashing) [cite: 802]
* [cite_start]**Framework:** .NET Framework [cite: 594]

## 🚀 Getting Started

### Prerequisites

1.  [cite_start]A Windows 10 or later operating system[cite: 683].
2.  [cite_start].NET Framework 4.7.2 or later[cite: 683].
3.  [cite_start]A local installation of MySQL for the backend database[cite: 671].

### Installation

1.  Clone the repository:
    ```bash
    git clone [YOUR-REPOSITORY-URL-HERE]
    ```
2.  [cite_start]Set up the MySQL database (refer to the `[DatabaseSchema.sql]` file in the repository for table creation: `Users`, `Income`, `Expenses`, `Reminders`)[cite: 674, 675].
3.  Open the solution file (`.sln`) in **Visual Studio**.
4.  Update the database connection string in the configuration file to point to your local MySQL instance.
5.  Run the application by pressing `F5` in Visual Studio.

## 📈 Future Enhancements

Potential improvements to be integrated in future releases include:

1.  [cite_start]**Integration with External Systems:** Connecting with external banking systems for automated transaction logging[cite: 555].
2.  [cite_start]**Mobile Application Development:** Extending the service to a mobile platform[cite: 538].
3.  [cite_start]**Advanced Planning:** Adding tools for debt management, savings goal tracking, and export functionality[cite: 707].
