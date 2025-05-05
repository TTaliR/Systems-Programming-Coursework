# C Programming Projects Collection

This repository contains three separate C-based projects developed for systems programming coursework. Each project demonstrates different aspects of C programming including file I/O, process management, user handling, and inter-process communication.

## 📁 Projects

### 1. Word Filter and Counter
Path: `Project1_WordFilterAndCounter/`

A command-line utility written in C that reads an input file, filters words based on given criteria, and counts occurrences. Useful for basic text processing and statistics.

- **Main file:** `WordCounterAndFilter.c`
- **Features:** Word filtering, frequency counting, file input/output

---

### 2. User Management System
Path: `Project2_UserManagement/`

This set of programs handles basic user record operations such as adding and checking users. It simulates multi-process behavior using child processes.

- **Main files:**
  - `add_user.c`
  - `check_user.c`
  - `child_add.c`
- **Features:** File-based user management, child process logic

---

### 3. Inter-Process Communication via FIFOs and Pipes
Path: `Project3_IPC_FIFOsPipes/`

Implements producer-consumer architecture using both FIFOs and unnamed pipes. Ideal for demonstrating Linux IPC mechanisms.

- **Main files:**
  - `fifo_producer.c`
  - `fifo_consumer.c`
  - `pipes.c`
- **Features:** Blocking FIFO communication, pipe-based data flow

---

## 🛠 Build and Run

Use `gcc` to compile individual `.c` files. Example:

```bash
gcc WordCounterAndFilter.c -o word_counter
./word_counter input.txt
```

Repeat for other files depending on the desired program.

---

## 📄 License

This repository is intended for educational purposes only.
