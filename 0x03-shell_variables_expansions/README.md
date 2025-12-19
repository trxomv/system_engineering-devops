# 🧰 0x03-shell_variables_expansions

## 📘 Contents
1. [Overview](#-overview)
2. [Directory Structure](#-directory-structure)
3. [Learning Outcomes](#-learning-outcomes)
4. [How to Run the Scripts](#-how-to-run-the-scripts)
5. [Author](#%E2%80%8D-author)

---

## 📘 Overview
This directory contains Bash scripts that focus on **shell variables** and **expansions** in Linux.  
These scripts explore how to handle local and global environment variables, manipulate the shell environment, and perform arithmetic operations directly within the shell. They are part of the **_ALX Pathway program_** System Engineering & DevOps track.

Each script performs a clearly defined task such as:
- Creating aliases
- Manipulating the `$PATH` variable
- Creating local and global variables
- Listing environment variables
- Performing arithmetic operations (Addition, Division, Exponentiation)

---

## 📁 Directory Structure
```text
system_engineering-devops/
├── 0x00-shell_basics/
├── 0x01-shell_permissions/
├── 0x02-shell_redirections/
├── 0x03-shell_variables_expansions/
│   ├── 0-alias
│   ├── 1-hello_you
│   ├── 2-path
│   ├── 3-paths
│   ├── 4-global_variables
│   ├── 5-local_variables
│   ├── 6-create_local_variable
│   ├── 7-create_global_variable
│   ├── 8-true_knowledge
│   ├── 9-divide_and_rule
│   ├── 10-love_exponent_breath
│   └── README.md
├── 0x04-loops_conditions_and_parsing/
├── 0x05-processes_and_signals/
└── README.md

### ⚙️ Scripts Description

<table>
  <tr>
    <th>File Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><code>0-alias</code></td>
    <td>Creates an alias for <code>ls</code> that executes <code>rm *</code>.</td>
  </tr>
  <tr>
    <td><code>1-hello_you</code></td>
    <td>Prints <code>hello</code> followed by the current Linux username.</td>
  </tr>
  <tr>
    <td><code>2-path</code></td>
    <td>Adds <code>/action</code> to the end of the <code>PATH</code> variable.</td>
  </tr>
  <tr>
    <td><code>3-paths</code></td>
    <td>Counts the number of directories in the <code>PATH</code> variable.</td>
  </tr>
  <tr>
    <td><code>4-global_variables</code></td>
    <td>Lists all global environment variables using <code>printenv</code>.</td>
  </tr>
  <tr>
    <td><code>5-local_variables</code></td>
    <td>Lists all local variables, environment variables, and functions using <code>set</code>.</td>
  </tr>
  <tr>
    <td><code>6-create_local_variable</code></td>
    <td>Creates a new local variable named <code>BEST</code> with the value <code>School</code>.</td>
  </tr>
  <tr>
    <td><code>7-create_global_variable</code></td>
    <td>Creates a new global variable named <code>BEST</code> with the value <code>School</code>.</td>
  </tr>
  <tr>
    <td><code>8-true_knowledge</code></td>
    <td>Prints the result of adding 128 to the value of <code>TRUEKNOWLEDGE</code>.</td>
  </tr>
  <tr>
    <td><code>9-divide_and_rule</code></td>
    <td>Prints the result of dividing <code>POWER</code> by <code>DIVIDE</code>.</td>
  </tr>
  <tr>
    <td><code>10-love_exponent_breath</code></td>
    <td>Prints the result of <code>BREATH</code> raised to the power of <code>LOVE</code>.</td>
  </tr>
</table>

---

## 🧠 Learning Outcomes
After completing the tasks in this directory, I learned how to:

- Create and use aliases in Bash.
- Differentiate between local and global (environment) variables.
- Manipulate the `$PATH` environment variable.
- Count elements within a variable using piping and `tr`.
- Perform arithmetic operations in Bash using expansion `(( ))`.
- Use commands like `export`, `source`, `printenv`, and `set`.

---

## 🚀 How to Run the Scripts

Each file is an executable Bash script.  
To run them, follow these steps inside your terminal:


### 1️⃣ Make sure you're in the correct directory
```bash
cd 0x03-shell_variables_expansions
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
chmod +x 1-hello_you
```
```bash
./1-hello_you
```
##### Output
```bash
hello username
```
---

## 👨‍💻 Author

**Omar Ihab Hammam El-Shewy**  
💼 Front-end Developer | Currently studying Cybersecurity and the ALX Pathway Program  
[LinkedIn](https://www.linkedin.com/in/omar-elshewy7/)
