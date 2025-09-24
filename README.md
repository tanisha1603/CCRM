[README.md](https://github.com/user-attachments/files/22521983/README.1.md)
# Campus Course & Records Manager (CCRM)

## Project Overview
**Campus Course & Records Manager (CCRM)** is a console-based Java application designed to manage:
- Students (create/update, enroll/unenroll in courses)
- Courses (create/update, assign instructors, list/search)
- Grades & Transcripts (record marks, compute GPA, print transcripts)
- File Utilities (import/export CSV/JSON)

This project demonstrates Java concepts including OOP, file handling, collections, exception handling, and basic console-based UI.

### How to Run
1. **JDK Version:** Java 17 or above
2. **Compile:**  
   ```bash
   javac -d bin src/*.java
   ```
3. **Run:**  
   ```bash
   java -cp bin Main
   ```

---

## Evolution of Java
- **1991:** Java started as Oak by Sun Microsystems  
- **1995:** Officially released as Java 1.0  
- **1998:** Java 2 (J2SE, J2EE, J2ME) introduced  
- **2004:** Java 5 introduced generics and metadata  
- **2011:** Java 7 with try-with-resources  
- **2014:** Java 8 introduced lambda expressions & Stream API  
- **2021:** Java 17 LTS (current long-term support)  

---

## Java Editions Comparison

| Feature       | Java SE (Standard Edition) | Java EE (Enterprise Edition) | Java ME (Micro Edition) |
|---------------|---------------------------|-----------------------------|------------------------|
| Purpose       | Core Java applications    | Enterprise web apps         | Embedded/mobile apps   |
| API Scope     | Collections, IO, etc.    | Servlets, JSP, EJB          | Lightweight APIs       |
| Platform      | Desktop/Server           | Server                     | Mobile/IoT             |
| Complexity    | Low to Medium            | High                        | Low                    |

---

## JDK, JRE, JVM Explanation
- **JVM (Java Virtual Machine):** Runs compiled bytecode (`.class`) on any platform.  
- **JRE (Java Runtime Environment):** JVM + libraries to run Java apps.  
- **JDK (Java Development Kit):** JRE + compiler and development tools for creating Java programs.  

---

## Windows Installation & Eclipse Setup

### Install Java on Windows
1. Download **JDK 17** from [Oracle](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html).  
2. Run the installer and set the **JAVA_HOME** environment variable.  
3. Add `%JAVA_HOME%\bin` to the **PATH** environment variable.  
4. Verify installation:
   ```bash
   java -version
   ```

![Windows Install](path_to_windows_install_image.png)

### Setup Eclipse
1. Download **Eclipse IDE for Java Developers** from [Eclipse](https://www.eclipse.org/downloads/).  
2. Install and launch Eclipse.  
3. Create a new Java project: `File → New → Java Project`  
4. Import your source files (`src` folder) into the project.  

![Eclipse Setup](path_to_eclipse_setup_image.png)

---

## Mapping Table: Syllabus Topic → Implementation

| Syllabus Topic                  | File/Class/Method                |
|---------------------------------|--------------------------------|
| Student Management              | `Student.java`, `StudentManager.java` |
| Course Management               | `Course.java`, `CourseManager.java`   |
| Enrollment & Grades             | `Enrollment.java`, `GradeManager.java` |
| File I/O (CSV/JSON)             | `FileUtils.java`                |
| Console Menu & UI               | `Main.java`, `Menu.java`        |

---

## Notes on Enabling Assertions
Assertions help check program assumptions during runtime.

1. Enable assertions when running the program:
   ```bash
   java -ea -cp bin Main
   ```
2. Example in code:
   ```java
   int marks = getMarks();
   assert marks >= 0 : "Marks cannot be negative";
   ```

---

*Developed by: Tanisha Tiwari*
