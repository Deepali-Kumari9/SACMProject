# 📚 Campus Course & Records Manager (CCRM)

This project is a console-based Java application for managing student and course records, including enrollment, grading, and file operations. It showcases key **Object-Oriented Programming (OOP)** principles, robust **exception handling**, modern **NIO.2 file I/O**, **Java Streams**, and various **Design Patterns**.


## 🚀 Project Overview

The CCRM system provides a menu-driven interface to manage students, courses, grades, and transcripts. It includes comprehensive file utilities for data import, export, and backups, ensuring data integrity and persistence.

### **How to Run**

1.  **Prerequisites**: Ensure you have a recent **Java Development Kit (JDK)** version installed on your system.
2.  **Execution**: Navigate to the `edu.sacm.cli` package within the project directory.
3.  **Command**: Run the `SACMApp.java` file. The application will launch a command-line interface from which you can perform all operations.


## 💡 Java Concepts & Architecture

### **Evolution of Java**

-   **1995**: Java was introduced as a platform-independent, object-oriented language.
-   **Java SE (Standard Edition)**: The core platform for building desktop and console applications, such as this CCRM project.
-   **Java EE (Enterprise Edition)**: A platform for developing large-scale, distributed enterprise applications.
-   **Java ME (Micro Edition)**: A platform for building applications for mobile devices and embedded systems.

### **JDK, JRE, and JVM**

-   **JDK (Java Development Kit)**: The complete software development environment for building Java applications. It includes the JRE, a compiler (`javac`), and other development tools.
-   **JRE (Java Runtime Environment)**: Contains the necessary libraries and the **JVM** to execute Java programs. You need a JRE to run compiled Java code.
-   **JVM (Java Virtual Machine)**: The core component that enables Java's platform independence. It interprets and executes the compiled Java bytecode, allowing the same code to run on any machine with a compatible JRE. 


## 💻 Setup and Environment

This section provides visual guidance for setting up the project on a Windows environment using the Eclipse IDE.

-   **Windows Installation**: Screenshots in the `screenshots/` folder show the successful installation of the JDK, verified using the `java -version` command.
-   **Eclipse Setup**: The `screenshots/` folder also contains images illustrating how to import the project into the Eclipse IDE and the resulting folder structure in the Project Explorer.


## 🔗 Concept Mapping

The table below maps key project requirements and academic concepts to their corresponding implementation files or classes.

| Syllabus Topic | File/Class/Method |
| :--- | :--- |
| **Custom Exceptions** | `DuplicateEnrollmentException.java`, `MaxCreditLimitExceededException.java` |
| **Assertions** | Assertions are used for internal invariant checks. To enable, use the `-ea` flag when running the JVM. For example, `java -ea SACMApp`. |
| **Enums with Fields** | `Grade.java`, `Semester.java` |
| **Polymorphism** | `Student::printProfile()` method, which overrides the base `Person` class method to display specific student information. |
| **NIO.2 (File I/O)** | `FileUtil.java` for creating file backups and calculating file sizes. |
| **Streams & Lambdas** | `EnrollmentService.java` for efficient filtering and summing of student credits. |
| **Builder Pattern** | `Course.Builder` inner class, which provides a flexible way to construct `Course` objects. |
| **Singleton Pattern** | `AppConfig.java` class, ensuring only one instance of the application configuration exists. |
| **`toString()` Override** | `Student.java`, `Course.java`, `Enrollment.java` to provide clear, human-readable representations of objects. |
| **Interfaces** | _This project does not use interfaces._ Class inheritance was chosen to establish a clear `Person` and `Student` domain model hierarchy. |


## 📄 Project Documentation & Usage

-   **Screenshots Folder**: The `screenshots/` folder contains all images required for project submission, including setup and execution examples.
-   **Usage Guide**: A separate `USAGE.md` file (or a section below) details the menu-driven CLI, providing sample commands and data files to demonstrate the application's functionality. This ensures a seamless testing experience.

Test Data Folder: A simple test-data folder is included, which contains small CSVs for import functionality.

Expected Output
The expected output for this project is a Git repository link containing the complete source code, a 
README.md file, a screenshots folder, and a test-data folder.
