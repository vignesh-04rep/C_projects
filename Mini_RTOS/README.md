# 🕒 Mini RTOS in C

## 🔹 Overview
This project implements a **Mini Real-Time Operating System (RTOS)** in C, designed for learning and embedded systems practice. It demonstrates fundamental RTOS concepts such as **task scheduling, context switching, and inter-task communication** on microcontrollers.

---

## 🔹 Features
- 🕒 Task Scheduling (round-robin / priority-based)
- 🔄 Context Switching (cooperative or preemptive)
- 📦 Task Management (create, delete, manage tasks)
- 📡 Inter-task Communication (message queues, semaphores)
- ⏱️ Timer Support (basic tick timer)
- ⚡ Lightweight kernel for small MCUs

---

## 🔹 Project Structure
mini-rtos/ │── src/ │ ├── rtos.c # Core RTOS kernel │ ├── scheduler.c # Task scheduling logic │ ├── tasks.c # Example user tasks │ └── main.c # Entry point │ │── include/ │ ├── rtos.h # Kernel API definitions │ ├── scheduler.h # Scheduler interface │ └── tasks.h # Task prototypes │ │── docs/ │ └── README.md # Project documentation


---

## 🔹 Getting Started

### Prerequisites

- Basic knowledge of C and embedded systems

### Build & Run
# Clone the repo
https://github.com/vignesh-04rep/C_projects
cd mini-rtos

# Compile (example with GCC)
gcc src/*.c -Iinclude -o mini-rtos

# Run (simulation or hardware)
./mini-rtos

🔹 License
Released under the MIT License. Free to use, modify, and share.
