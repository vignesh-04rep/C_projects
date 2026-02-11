# 🐚 My Shell Project

A simple custom shell written in **C** that provides a command-line interface with basic features such as directory navigation (`cd`), command execution using `system()` calls, and an interactive prompt. It continuously accepts user input, processes commands, and supports termination with the `Exit` keyword. This project demonstrates core concepts of **process control, system calls, and string handling** in Unix-like environments.

---

## ✨ Features
- 🖥️ Custom shell prompt (`MY SHELL >`)
- ⚡ Execute standard Linux/Unix commands
- 📂 Change directories using `cd`
- 🚪 Exit gracefully with `Exit`
- 🔧 Demonstrates system calls and string manipulation

---

## 🚀 Usage
1. **Compile the code**
   ```bash
   gcc SHELL.c -o myshell

2.**RUN THE SHELL
```bash
  ./myshell

3.INTERACT WITH THE SHELL
-Type commands like ls, pwd, or gcc file.c o file to execute them.
-Use cd <directory> to change directories.
-Type Exit to quit the shell.


---
🔮 Future Improvements
➕ Add support for piping (|) and redirection (>, <)

🧵 Implement background process handling (&)

🛡️ Enhance error handling and command validation

📜 Add history and auto-completion features

---

📚 Learning Outcome
This project is a hands-on demonstration of building a minimal shell environment, showcasing fundamental concepts in operating systems, embedded C programming, and Unix system calls.



