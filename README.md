# Test-2-Day-7

# JavaFX CRUD Application

## Description

This project is a JavaFX desktop application demonstrating a login screen and CRUD (Create, Read, Update, Delete) operations on a MySQL database. The app is built using Java, JavaFX, and JDBC for database connectivity.

---

## Features

- User login interface  
- CRUD operations on student records (add, view, update, delete)  
- JavaFX GUI with TableView to display data  
- Connection to local MySQL database  

---

## Technologies Used

- Java 17+  
- JavaFX 24  
- MySQL  
- JDBC  

---

## Project Status

- The core JavaFX application logic, including controllers and models, is implemented and functional.  
- Database connectivity via JDBC is configured and tested locally.  
- The UI design includes FXML files for the login and CRUD views.

### Known Issue

Currently, the application fails to launch due to resource loading errors related to FXML files not being found at runtime. This is caused by IDE or build configuration issues affecting resource packaging.

Despite this, all backend and GUI logic code is complete and can be tested independently.

---

## Setup Instructions

1. Install Java JDK 17 or higher.  
2. Install MySQL and create a database named `school_app` with a `students` table having columns:
   - `id` INT PRIMARY KEY AUTO_INCREMENT  
   - `name` VARCHAR(255)  
   - `email` VARCHAR(255)  
3. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/yourrepo.git
