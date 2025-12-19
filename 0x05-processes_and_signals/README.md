# 🧰 0x05-processes_and_signals

## 📘 Contents
1. [Overview](#-overview)
2. [Directory Structure](#-directory-structure)
3. [Scripts Description](#%EF%B8%8F-scripts-description)
4. [Learning Outcomes](#-learning-outcomes)
5. [How to Run the Scripts](#-how-to-run-the-scripts)
6. [Author](#%E2%80%8D-author)

---

## 📘 Overview
This directory contains Bash scripts that focus on **Linux processes and signals**.  
Understanding how processes work, how to retrieve their IDs (PIDs), and how to control them using signals is a core skill in **system administration**, **DevOps**, and **shell scripting**.

The tasks in this directory demonstrate how to:
- Identify running processes and their PIDs.
- Create scripts that run indefinitely.
- Stop processes using different methods and signals.
- Handle and trap signals inside Bash scripts.
- Understand the difference between **graceful termination** and **forceful termination**.

These scripts are part of the **_ALX Pathway Program_** — System Engineering & DevOps track.

---

## 📁 Directory Structure
```text
system_engineering-devops/
├── 0x00-shell_basics/
├── 0x01-shell_permissions/
├── 0x02-shell_redirections/
├── 0x03-shell_variables_expansions/
├── 0x04-loops_conditions_and_parsing/
├── 0x05-processes_and_signals/
│   ├── 0-what-is-my-pid
│   ├── 3-show_your_bash_pid_made_easy
│   ├── 4-to_infinity_and_beyond
│   ├── 5-dont_stop_me_now
│   ├── 6-stop_me_if_you_can
│   ├── 7-highlander
│   ├── 67-stop_me_if_you_can
│   ├── 8-beheaded_process
│   └── README.md
└── README.md
```
### ⚙️ Scripts Description

<table>
  <tr>
    <th>File Name</th>
    <th>Concept</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><code>0-what-is-my-pid</code></td>
    <td>PID</td>
    <td>Displays the Process ID (PID) of the script itself.</td>
  </tr>
  <tr>
    <td><code>3-show_your_bash_pid_made_easy</code></td>
    <td>Process lookup</td>
    <td>Displays the PID and process name of all running processes containing the word <code>bash</code>, without using <code>ps</code>.</td>
  </tr>
  <tr>
    <td><code>4-to_infinity_and_beyond</code></td>
    <td>Infinite loowp</td>
    <td>Runs indefinitely, printing <code>"To infinity and beyond"</code> every 2 seconds.</td>
  </tr>
  <tr>
    <td><code>5-dont_stop_me_now</code></td>
    <td>Process termination</td>
    <td>Stops the <code>4-to_infinity_and_beyond</code> process using the <code>kill</code> command.</td>
  </tr>
  <tr>
    <td><code>6-stop_me_if_you_can</code></td>
    <td>Alternative termination</td>
    <td>Stops the <code>4-to_infinity_and_beyond</code> process without using <code>kill</code> or <code>killall</code>.</td>
  </tr>
  <tr>
    <td><code>7-highlander</code></td>
    <td>Signal handling</td>
    <td>Runs indefinitely and traps the <code>SIGTERM</code> signal, printing <code>"I am invincible!!!"</code> instead of terminating.</td>
  </tr>
  <tr>
    <td><code>67-stop_me_if_you_can</code></td>
    <td>Signal testing</td>
    <td>Sends a <code>SIGTERM</code> signal to the <code>7-highlander</code> process to demonstrate signal trapping.</td>
  </tr>
  <tr>
    <td><code>8-beheaded_process</code></td>
    <td>SIGKILL</td>
    <td>Forcefully terminates the <code>7-highlander</code> process using the <code>SIGKILL</code> (signal 9).</td>
  </tr>
</table>
---

## 🧠 Learning Outcomes
After completing the tasks in this directory, I gained a solid understanding of how to:

- Retrieve the PID of the currently running script.
- Identify running processes by name.
- Create and manage infinite loops in Bash.
- Stop processes using different approaches and commands.
- Understand and use Linux signals such as:
 - `SIGTERM` (graceful termination)
 - `SIGINT` (Ctrl+C)
 - `SIGKILL` (forceful termination)
- Trap and handle signals inside Bash scripts.
- Differentiate between signals that can be handled and signals that cannot be ignored.

---

## 🚀 How to Run the Scripts

Each file is an executable Bash script.  
To run them, follow these steps inside your terminal:


### 1️⃣ Make sure you're in the correct directory
```bash
cd 0x05-processes_and_signals
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
chmod +x 0-what-is-my-pid
```
```bash
./0-what-is-my-pid
```
##### Output
```bash
40333
```
---

## 👨‍💻 Author

**Omar Ihab Hammam El-Shewy**  
💼 Front-end Developer | Currently studying Cybersecurity and the ALX Pathway Program  
[LinkedIn](https://www.linkedin.com/in/omar-elshewy7/)
