# Financial Navigator: The SAD Case Study for University Financial Management

[![Project Type](https://img.shields.io/badge/Project%20Type-System%20Analysis%20%26%20Design%20(SAD)-orange.svg)]()
[![Core Skill](https://img.shields.io/badge/Focus-Business%20Analysis-blue.svg)]()

## 💡 The Business Problem: Bridging the Financial Literacy Gap

University students face unique financial challenges: balancing limited income (stipends, part-time jobs, financial aid) against variable expenses (rent, books, social life). Our analysis revealed that existing commercial apps often fail to integrate student-specific needs, leading to overspending and significant financial stress.

**Project Goal:** To design, analyze, and propose a user-centric desktop application to facilitate effective budgeting, expense tracking, and financial planning for this underserved demographic.

---

## 🔎 Phase 1: Deep Dive Analysis & Requirements Gathering

This section showcases the foundational work that drove the entire system design.

### A. Requirements Elicitation
We employed a mixed-method approach to gather accurate user needs:
* **Stakeholder Interviews:** Conducted targeted interviews with university students (as documented in **Interviews with university students.pdf**) to identify core pain points, feature desires, and existing budgeting methods.
* **Gap Analysis:** Analyzed existing solutions to define what was missing, leading to the requirement for specific features like **Financial Aid Integration** and a secure, non-cloud-based tracking system.

### B. Feasibility Study & ROI Justification
The project's viability was assessed across four dimensions, culminating in a strong economic justification.

| Feasibility Dimension | Outcome / Key Finding |
| :--- | :--- |
| **Operational** | High user acceptance due to tailored features. System addresses a critical, unsolved operational gap for students. |
| **Technical** | C# and MySQL were selected as a mature, stable, and cost-effective stack. **Low technical risk.** |
| **Schedule** | Project completion was feasible within the **42-day timeframe** (as per **Project Proposal**). |
| **Economic** | Calculated a highly favorable **Return on Investment (ROI) of 66.67%** and a projected payback period of **7.2 months**. *This demonstrates the project's measurable business value.* |

---

## 📐 Phase 2: System Design & Modeling Artifacts

The analysis translated directly into robust, traceable design specifications.

### A. System Requirement Specification (SRS)
A comprehensive SRS was developed to document the approved **Functional** (e.g., track income/expense, generate reports) and **Non-Functional** (e.g., security using BCrypt, high usability) requirements, ensuring alignment with user needs.

### B. Architecture and Modeling (UML)
We used standard UML diagrams to communicate the system's structure and behavior to the development team.

| Artifact | Purpose for the BA | **Image / Document Reference** |
| :--- | :--- | :--- |
| **Use Case Diagram** | Defined all interactions between the user and the system (e.g., Log In, Track Expense, Set Reminder). | *[Link to Use Case Diagram image in your report]* |
| **Class Diagram** | Identified the core entities (User, Income, Expense, Budget) and their relationships, laying the groundwork for the database schema. | *[Link to Class Diagram image in your report]* |
| **Activity Diagram** | Mapped the flow of complex processes, such as the *Expense Tracking Process*, ensuring logical and efficient design. | *[Link to Activity Diagram image in your report]* |

### **Example Visual: The Use Case Diagram**

*(This is where you would include the image/screenshot from your document to make it visually impressive. If you cannot upload the image, keep the placeholder text.)*

**[PLACEHOLDER FOR USE CASE DIAGRAM IMAGE]**

---

## 💻 The Final Solution (Brief Technical Summary)

The design culminated in a functional proof-of-concept desktop application.

| Component | Technology | Why it was Chosen |
| :--- | :--- | :--- |
| **Client** | **C# Windows Forms** | Provides a secure, standalone, and responsive native user experience required by the students surveyed. |
| **Database** | **MySQL** | Reliable, open-source, and efficient solution for handling the user's personal financial data. |
| **Security** | **BCrypt Hashing** | Ensures **Non-Functional Requirement** compliance by securely handling user authentication data. |

### Conclusion

This project demonstrates proficiency across the full SAD lifecycle: from identifying an operational gap, conducting rigorous requirements gathering, performing a value-driven **Feasibility Study (ROI 66.67%)**, and documenting the system using industry-standard modeling techniques.

---
