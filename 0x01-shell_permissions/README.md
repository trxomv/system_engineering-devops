# 🧰 0x01-shell_permissions

## 📘 Contents
1. [Overview](#-overview)
2. [Directory Structure](#-directory-structure)
3. [Learning Outcomes](#-learning-outcomes)
4. [How to Run the Scripts](#-how-to-run-the-scripts)
5. [Author](#%E2%80%8D-author)

---

## 📘 Overview
This directory contains Bash scripts that focus on Linux users, groups, file ownership, and permission management.  
These scripts form the foundation of Linux system administration and security, and they are part of the **_ALX Pathway program_** System Engineering & DevOps track.  

Each script performs one clearly defined task-such as:
- switching users
- creating files
- modifying ownership
- setting specific permission modes.

---

## 📁 Directory Structure
```text
system_engineering-devops/
├── 0x00-shell_basics/
├── 0x01-shell_permissions/
│ ├── 0-iam_betty
│ ├── 1-who_am_i
│ ├── 2-groups
│ ├── 3-new_owner
│ ├── 4-empty
│ ├── 5-execute
│ ├── 8-James_Bond
│ ├── 9-John_Doe
│ ├── 11-directories_permissions
│ ├── 12-directory_permissions
│ ├── 13-change_group
│ └── README.md
├── 0x02-shell_redirections/
├── 0x03-shell_variables_expansions/
├── 0x04-loops_conditions_and_parsing/
├── 0x05-processes_and_signals/
└── README.md
```
### ⚙️ Scripts Description

<table>
  <tr>
    <th>File Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><code>0-iam_betty</code></td>
    <td>Switches the current user to betty.</td>
  </tr>
  <tr>
    <td><code>1-who_am_i</code></td>
    <td>Prints the effective username of the current user.</td>
  </tr>
  <tr>
    <td><code>2-groups</code></td>
    <td>Displays all groups the current user belongs to.</td>
  </tr>
    <tr>
    <td><code>3-new_owner</code></td>
    <td>Changes the owner of the file <code>hello</code> to betty.</td>
  </tr>
    <tr>
    <td><code>4-empty</code></td>
    <td>Creates an empty file named <code>hello</code>.</td>
  </tr>
    <tr>
    <td><code>5-execute</code></td>
    <td>Adds execute permission to the owner of the file <code>hello</code>.</td>
  </tr>
    <tr>
    <td><code>8-James_Bond</code></td>
    <td>Sets <code>hello</code> permissions to <code>-------rwx</code> (owner: none, group: none, others: all).</td>
  </tr>
    <tr>
    <td><code>9-John_Doe</code></td>
    <td>Sets <code>hello</code> permissions to <code>-rwxr-x-wx</code> (owner: rwx, group: r-x, others: -wx).</td>
  </tr>
    <tr>
    <td><code>11-directories_permissions</code></td>
    <td>Adds execute permission to all subdirectories of the current directory for all users.</td>
  </tr>
    <tr>
    <td><code>12-directory_permissions</code></td>
    <td>Creates a directory <code>my_dir</code> with permissions 751.</td>
  </tr>
    <tr>
    <td><code>13-change_group</code></td>
    <td>Changes the group owner of the file <code>hello</code> to <code>school</code>.</td>
</table>

---

## 🧠 Learning Outcomes
After completing the tasks in this directory, I learned how to:
- Switch between users and verify the effective user.
- Understand and list group memberships.
- Create and manage files and directories.
- Change file ownership and group ownership.
- Apply precise permissions to files and directories.

---

## 🚀 How to Run the Scripts

Each file is an executable Bash script.  
To run them, follow these steps inside your terminal:


### 1️⃣ Make sure you're in the correct directory
```bash
cd 0x01-shell_permissions
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
chmod +x 1-who_am_i
```
```bash
./1-who_am_i
```
##### Output
```bash
username
```
---

## 👨‍💻 Author

**Omar Ihab Hammam El-Shewy**  
💼 Front-end Developer | Currently studying Cybersecurity and the ALX Pathway Program  
[LinkedIn](https://www.linkedin.com/in/omar-elshewy7/)
