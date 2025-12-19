# 🧰 x04-loops_conditions_and_parsing

## 📘 Contents
1. [Overview](#-overview)
2. [Directory Structure](#-directory-structure)
3. [Learning Outcomes](#-learning-outcomes)
4. [How to Run the Scripts](#-how-to-run-the-scripts)
5. [Author](#%E2%80%8D-author)

---

## 📘 Overview
This directory contains Bash scripts that focus on **loops**, **conditional statements**, and **file parsing** in the Linux shell. These constructs are vital for automating complex tasks and creating dynamic, responsive scripts.

The tasks are designed to demonstrate mastery over:
* The three main looping structures: `for`, `while`, and `until`.
* Conditional branching using `if`, `elif`, `else`, and `case` statements.
* Combining loops with conditionals to create logic-driven programs.
* Using file test operators to check file properties.

These scripts are part of the **_ALX Pathway program_** System Engineering & DevOps track.

---

## 📁 Directory Structure
```text
system_engineering-devops/
├── 0x00-shell_basics/
├── 0x01-shell_permissions/
├── 0x02-shell_redirections/
├── 0x03-shell_variables_expansions/
├── 0x04-loops_conditions_and_parsing/
│   ├── 1-for_best_school
│   ├── 2-while_best_school
│   ├── 3-until_best_school
│   ├── 4-if_9_say_hi
│   ├── 5-4_bad_luck_8_is_your_chance
│   ├── 6-superstitious_numbers
│   ├── 8-for_ls
│   ├── 9-to_file_or_not_to_file
│   └── README.md
├── 0x05-processes_and_signals/
└── README.md
```
### ⚙️ Scripts Description

<table>
  <tr>
    <th>File Name</th>
    <th>Loop Type</th>
    <th>Conditional Structure</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><code>1-for_best_school</code></td>
    <td><code>for</code></td>
    <td><code>N/A</code></td>
    <td>Displays "Best School" exactly 10 times using a <code>for</code>loop.</td>
  </tr>
  <tr>
    <td><code>2-while_best_school</code></td>
    <td><code>while</code></td>
    <td><code>N/A</code></td>
    <td>Displays "Best School" exactly 10 times using a <code>while</code>loop.</td>
  </tr>
  <tr>
    <td><code>3-until_best_school</code></td>
    <td><code>until</code></td>
    <td><code>N/A</code></td>
    <td>Displays "Best School" exactly 10 times using a <code>until</code>loop.</td>
  </tr>
  <tr>
    <td><code>4-if_9_say_hi</code></td>
    <td><code>while</code></td>
    <td><code>if</code></td>
    <td>Displays "Best School" 10 times, adding "Hi" on a new line for the 9th iteration.</td>
  </tr>
  <tr>
    <td><code>5-4_bad_luck_8_is_your_chance</code></td>
    <td><code>while</code></td>
    <td><code>if-elif-else</code></td>
    <td>Loops from 1 to 10, displaying "bad luck" for 4, "good luck" for 8, and "Best School" otherwise.</td>
  </tr>
  <tr>
    <td><code>6-superstitious_numbers</code></td>
    <td><code>while</code></td>
    <td><code>case</code></td>
    <td></code>Loops from 1 to 20, displaying specific "bad luck" messages for the numbers 4, 9, and 17 using a <code>case</code> statement.</td>
  </tr>
  <tr>
    <td><code>8-for_ls</code></td>
    <td><code>for</code></td>
    <td><code>N/A</code></td>
    <td></code>Lists files in the current directory, displaying only the part of the name after the first dash (<code>-</code>).</td>
  </tr>
  <tr>
    <td><code>9-to_file_or_not_to_file</code></td>
    <td><code>N/A</code></td>
    <td><code>if-else</code></td>
    <td></code>Checks the file named <code>school</code> for existence, emptiness, and if it is a regular file, printing corresponding messages.</td>
  </tr>
</table>

---

## 🧠 Learning Outcomes
After completing the tasks in this directory, I gained a strong understanding of how to:

- Implement the`for` loop to iterate over a sequence (e.g., a list of numbers or files).
- Implement the `while` loop to repeat execution as long as a condition is true.
- Implement the `until` loop to repeat execution until a condition becomes true.
- Use the `if` statement for simple decision-making.
- Use the `if-elif-else` structure for handling multiple, mutually exclusive conditions.
- Use the `case` statement as a clean alternative to a long `if-elif` chain for matching specific values.
- Use string manipulation techniques (e.g., parameter expansion) within loops (Task 8).
- Employ file test operators (like `-f`, `-e`, `-s`) within conditional statements to check file existence, type, and size (Task 9).

---

## 🚀 How to Run the Scripts

Each file is an executable Bash script.  
To run them, follow these steps inside your terminal:


### 1️⃣ Make sure you're in the correct directory
```bash
cd 0x04-loops_conditions_and_parsing
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
chmod +x 1-for_best_school
```
```bash
./1-for_best_school
```
##### Output
```bash
Best School
Best School
... (8 more times)
```
---

## 👨‍💻 Author

**Omar Ihab Hammam El-Shewy**  
💼 Front-end Developer | Currently studying Cybersecurity and the ALX Pathway Program  
[LinkedIn](https://www.linkedin.com/in/omar-elshewy7/)
