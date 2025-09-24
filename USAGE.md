[USAGE.md](https://github.com/user-attachments/files/22522162/USAGE.md)
# Usage Guide for Campus Course & Records Manager (CCRM)

## Sample Commands

### Compile Project
```bash
javac -d bin src/*.java
```

### Run Project
```bash
java -cp bin Main
```

### Run with Assertions Enabled
```bash
java -ea -cp bin Main
```

---

## Sample Data Files

Place the CSV files in a folder named **test-data**:

- **student.csv** – contains student records  
- **course.csv** – contains course details  
- **enrollment.csv** – contains enrollments and grades  

### Example file path structure:

```
project_root/
 ├─ src/
 ├─ bin/
 └─ test-data/
     ├─ student.csv
     ├─ course.csv
     └─ enrollment.csv
```

---

## Sample Usage

1. Ensure CSV files are in **test-data** folder.  

2. Run the program using:  
   ```bash
   java -cp bin Main
   ```

3. Follow the console menu to:
   - Load student, course, and enrollment data  
   - Enroll students in courses  
   - Record grades  
   - Print transcripts  

---

**Developed by:** Tanisha Tiwari
