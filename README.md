# TaskMaster Pro (Simple Spring Boot App)

This is a **basic Spring Boot project** created for learning and practice. It demonstrates a simple **Task Manager** using Spring Boot MVC, Thymeleaf, and a minimal data layer.

This project is **not complex or production‑ready**, and that is totally fine. The goal is clarity and understanding.

---

## What this project does

- Displays a simple task page (`index.html`)
- Uses Spring Boot MVC architecture
- Basic CRUD-style structure (Controller, DAO, Model)
- Runs as a local Java web application

---

## Tech stack

- Java
- Spring Boot
- Maven
- Thymeleaf (HTML templates)

---

## Project structure (simple explanation)

```
TaskMaster_Pro
├── src/main/java/in/taskmaster_pro
│   ├── TaskMasterProApplication.java   # Main entry point
│   ├── controller/TaskController.java  # Handles HTTP requests
│   ├── dao/TaskDAO.java                # Data access logic
│   └── model/Task.java                 # Task model
│
├── src/main/resources
│   ├── templates/index.html            # UI page
│   └── application.properties          # App configuration
│
├── pom.xml                              # Maven dependencies
└── mvnw / mvnw.cmd                      # Maven wrapper

```

---

## How to run locally

### Prerequisites

- Java 17 (or compatible version)
- Maven (or use Maven Wrapper)

### Steps

```bash
# open project folder
cd TaskMaster_Pro

# run using maven wrapper
./mvnw spring-boot:run

# (Windows)
mvnw.cmd spring-boot:run

```

Open browser and visit:

```
http://localhost:8080

```

---

---

## Learning purpose

This project is good for:

- Understanding Spring Boot basics
- MVC architecture
- Controller → DAO → Model flow
- Running Java web apps locally

You do **not** need a fancy README or deployment to prove learning.

---

## Future improvements (optional)

- Add database (MySQL / H2)
- Add REST APIs
- Add validation
- Convert to REST backend + React frontend

---

## Author

**Nabin Oli**

---

> Simple project. Clean structure. Correct direction. Keep going.
>
