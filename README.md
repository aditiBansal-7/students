# Student Records

This repository contains a **students.yaml** file that holds structured data about students, including their name, age, major, and GPA.

## 📂 File Structure

```
.
├── students.yaml  # YAML file containing student details
├── README.md      # Documentation file
```

## 📄 students.yaml Format
The **students.yaml** file follows this structured format:

```yaml
students:
  - name: Alice
    age: 21
    major: Computer Science
    gpa: 3.8
  - name: Bob
    age: 22
    major: Mathematics
    gpa: 3.5
  - name: Charlie
    age: 20
    major: Physics
    gpa: 3.9
  - name: David
    age: 23
    major: Chemistry
    gpa: 3.2
  - name: Eva
    age: 21
    major: Computer Science
    gpa: 3.7
```

## 📊 Student Data
| Name    | Age | Major             | GPA  |
|---------|-----|------------------|------|
| Alice   | 21  | Computer Science | 3.8  |
| Bob     | 22  | Mathematics      | 3.5  |
| Charlie | 20  | Physics          | 3.9  |
| David   | 23  | Chemistry        | 3.2  |
| Eva     | 21  | Computer Science | 3.7  |

## 🚀 Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/aditiBansal-7/students.git
   ```

2. Navigate to the repository:
   ```sh
   cd students
   ```

3. Open the `students.yaml` file in any text editor or parse it using a programming language like Python:
   ```python
   import yaml
   
   with open("students.yaml", "r") as file:
       data = yaml.safe_load(file)
       print(data)
   ```

## 🛠 Contributing
If you’d like to contribute by adding more student data, follow these steps:
1. Fork the repository.
2. Add your changes to `students.yaml`.
3. Commit and push your changes.
4. Submit a pull request.


---

🔗 **Author**: [Aditi Bansal](https://github.com/aditiBansal-7)
