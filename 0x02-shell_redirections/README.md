# 🧰 0x02-shell_redirections

## 📘 Contents
1. [Overview](#-overview)
2. [Directory Structure](#-directory-structure)
3. [Learning Outcomes](#-learning-outcomes)
4. [How to Run the Scripts](#-how-to-run-the-scripts)
5. [Author](#%E2%80%8D-author)

---

## 📘 Overview
This directory contains Bash scripts that focus on **shell redirections** in Linux.  
These scripts form the foundation of Linux system administration and scripting, and they are part of the **_ALX Pathway program_** System Engineering & DevOps track.  

Each script performs a clearly defined task such as:
- Printing messages to standard output
- Displaying files
- Duplicating lines
- Handling files with special characters
- Removing files recursively

---

## 📁 Directory Structure
```text
system_engineering-devops/
├── 0x00-shell_basics/
├── 0x01-shell_permissions/
├── 0x02-shell_redirections/
│ ├── 0-hello_world
│ ├── 1-confused_smiley
│ ├── 2-hellofile
│ ├── 3-twofiles
│ ├── 4-lastlines
│ ├── 5-firstlines
│ ├── 6-third_line
│ ├── 7-file
│ ├── 8-cwd_state
│ ├── 9-duplicate_last_line
│ ├── 10-no_more_js
│ └── README.md
└── README.md
```
### ⚙️ Scripts Description

<table>
  <tr>
    <th>File Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><code>0-hello_world</code></td>
    <td>Prints <code>Hello, World</code> followed by a new line.</td>
  </tr>
  <tr>
    <td><code>1-confused_smiley</code></td>
    <td>Displays a confused smiley: <code>(Ôo)'</code>.</td>
  </tr>
  <tr>
    <td><code>2-hellofile</code></td>
    <td>Displays the content of <code>/etc/passwd</code>.</td>
  </tr>
    <tr>
    <td><code>3-twofiles</code></td>
    <td>Displays the content of <code>/etc/passwd</code> and <code>/etc/hosts</code>.</td>
  </tr>
    <tr>
    <td><code>4-lastlines</code></td>
    <td>Shows the last 10 lines of <code>/etc/passwd</code>.</td>
  </tr>
    <tr>
    <td><code>5-firstlines</code></td>
    <td>Shows the first 10 lines of <code>/etc/passwd</code>.</td>
  </tr>
    <tr>
    <td><code>6-third_line</code></td>
    <td>Displays the third line of the file <code>iacta</code> (without using <code>sed</code>).</td>
  </tr>
    <tr>
    <td><code>7-file</code></td>
    <td>Creates a file with special characters in the name containing the text <code>Best School</code>.</td>
  </tr>
    <tr>
    <td><code>8-cwd_state</code></td>
    <td>Saves the current directory state (output of <code>ls -la</code>) into <code>ls_cwd_content</code>.</td>
  </tr>
    <tr>
    <td><code>9-duplicate_last_line</code></td>
    <td>Duplicates the last line of the file <code>iacta</code>.</td>
  </tr>
    <tr>
    <td><code>10-no_more_js</code></td>
    <td>Deletes all regular files with a <code>.js</code> extension in the current directory and all subfolders.</td>
</table>

---

## 🧠 Learning Outcomes
After completing the tasks in this directory, I learned how to:
- Print messages and special characters to standard output.
- Display content from system files.
- Extract specific lines from files.
- Handle files with special characters in filenames.
- Save the state of directories to files.
- Duplicate lines within files.
- Remove files recursively using shell scripting.

---

## 🚀 How to Run the Scripts

Each file is an executable Bash script.  
To run them, follow these steps inside your terminal:


### 1️⃣ Make sure you're in the correct directory
```bash
cd 0x02-shell_redirections
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
chmod +x 0-hello_world
```
```bash
./0-hello_world
```
##### Output
```bash
Hello, World
```
---

## 👨‍💻 Author

**Omar Ihab Hammam El-Shewy**  
💼 Front-end Developer | Currently studying Cybersecurity and the ALX Pathway Program  
[LinkedIn](https://www.linkedin.com/in/omar-elshewy7/)
