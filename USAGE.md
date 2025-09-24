# USAGE Guide

This document provides a simple guide for interacting with the Campus Course & Records Manager (CCRM) application.

### Running the Application
The application is a console-based, menu-driven program. To run it, navigate to the `edu.sacm.cli` package within your Eclipse project and run `SACMApp.java`.

### Sample Commands

Once the application is running, follow the on-screen menu to perform operations.

**1. Manage Students**
* **1. Add Student**:
    * Enter choice: `1`
    * RegNo: `24BCE11526`
    * Name: `Deepali Kumari`
    * Email: `deepali.24bce11526@vitbhopal.ac.in`
* **2. List Students**:
    * Enter choice: `2`

**2. Manage Courses**
* **1. Add Course**:
    * Enter choice: `2`
    * Code: `CSE2006`
    * Title: `Programming in Java`
    * Credits: `3`
    * Instructor name: `Mohd. Ishrat`
    * Department: `Scope`

**3. Enrollment / Grades**
* **1. Enroll student**:
    * Enter choice: `3`
    * Student RegNo: `24BCE11526`
    * Course Code: `CSE2006`
* **2. Assign grade**:
    * Enter choice: `3`
    * Student RegNo: `24BCE11526`
    * Course Code: `CSE2006`
    * Grade: `S`
* **3. Print transcript**:
    * Enter choice: `3`
    * Student RegNo: `24BCE11526`

**4. Export / Backup (demo)**
* **1. Run Backup**:
    * Enter choice: `4`
    * This will create a `backups` folder with timestamped files.

---

### Data Files
The `test-data/` folder contains sample CSV files that can be used for the import functionality.
