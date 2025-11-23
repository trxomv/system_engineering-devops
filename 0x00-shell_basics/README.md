# 🧰 system_engineering-devops

## 📘 Contents
1. [Project Overview](#-project-overview)
2. [Directory Structure](#-directory-structure)
3. [Learning Outcomes](#-learning-outcomes)
4. [How to Run the Scripts](#-how-to-run-the-scripts)
5. [Author](#%E2%80%8D-author)

---

## 📘 Project Overview
This project is part of the **Foundations of Linux and Version Control** learning track within the **ALX PATHWAY** Program.  
It introduces the fundamental Linux shell commands and scripting skills required for efficient navigation and file management in a Unix-based environment.

Throughout this project, I created multiple Bash scripts that perform essential system operations such as:
- Displaying the current working directory
- Listing files and directories
- Navigating to the home directory
- Displaying hidden files
- Viewing detailed directory contents in long format

---

## 📁 Directory Structure
```text
system_engineering-devops/
├── 0x00-shell_basics/
│ ├── 0-current_working_directory
│ ├── 1-listit
│ ├── 2-bring_me_home
│ ├── 3-listfiles
│ └── 4-listmorefiles
└── README.md
```
### ⚙️ Scripts Description

<table>
  <tr>
    <th>File Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><code>0-current_working_directory</code></td>
    <td>Prints the absolute path name of the current working directory.</td>
  </tr>
  <tr>
    <td><code>1-listit</code></td>
    <td>Displays the contents of the current directory.</td>
  </tr>
  <tr>
    <td><code>2-bring_me_home</code></td>
    <td>Changes the working directory to the user's home directory without using shell variables.</td>
  </tr>
    <tr>
    <td><code>3-listfiles</code></td>
    <td>Displays the current directory contents in a long format.</td>
  </tr>
    <tr>
    <td><code>4-listmorefiles</code></td>
    <td>Displays all files (including hidden ones) in long format.</td>
  </tr>
</table>

---

## 🧠 Learning Outcomes
By completing this project, I learned how to:
- Navigate the Linux file system using the terminal.
- Use basic commands such as `pwd`, `ls`, and `cd`.
- Differentiate between visible and hidden files.
- Combine command-line options for extended functionality (`-l`, `-a`, etc.).
- Write simple yet effective Bash scripts with proper permissions and structure.

---

## 🚀 How to Run the Scripts

Each file is an executable Bash script.  
To run them, follow these steps inside your terminal:


### 1️⃣ Make sure you're in the correct directory
```bash
cd 0x00-shell_basics
```

### 2️⃣ Give execute permission (only once per script)
```bash
chmod +x script_name
```

### 3️⃣ Run the script
```bash
./script_name
```
#### Example
```bash
chmod +x 4-listmorefiles
```
```bash
./4-listmorefiles
```
##### Output
```bash
total 28
drwxr-xr-x@ 2 user staff 204 Jan 25 00:29 .
drwxr-xr-x@ 4 user staff 1462 Jan 25 00:19 ..
-rwxr-xr-x@ 1 user staff 18 Jan 25 00:19 0-current_working_directory
-rwxr-xr-x@ 1 user staff 19 Jan 25 00:23 1-listit
-rwxr-xr-x@ 1 user staff 18 Jan 25 00:29 2-bring_me_home
-rwxr-xr-x@ 1 user staff 18 Jan 25 00:39 3-listfiles
-rwxr-xr-x@ 1 user staff 18 Jan 25 00:41 4-listmorefiles
```
---

## 👨‍💻 Author

**Omar Ihab Hammam El-Shewy**  
💼 Front-end Developer | Currently studying Cybersecurity and the ALX Pathway Program  
[LinkedIn](https://www.linkedin.com/in/omar-elshewy7/)

