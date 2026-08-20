# CS5302 – Operating Systems Lab

**Chennai Institute of Technology**

A collection of C programs and Shell scripts for the **CS5302 – Operating Systems Laboratory**. This repository contains implementations of all experiments prescribed in the lab syllabus, along with a few additional projects that explore operating system concepts beyond the syllabus.

---

## 📁 Repository Structure

### Experiment 1 – Installation of Windows OS

Commands and reference materials related to Windows operating system installation.

### Experiment 2 – UNIX Commands and Shell Programming

Contains Shell scripts covering various UNIX commands and programming concepts.

**Programs:** 8 Shell programs

### Experiment 3 – System Calls

Implementation of basic UNIX system calls:

* `fork()`
* `exit()`
* `getpid()`
* `wait()`
* `close()`

### Experiment 4 – CPU Scheduling Algorithms

* First Come First Serve (FCFS)
* Shortest Job First (SJF)
* Priority Scheduling
* Round Robin

### Experiment 5 – Inter-Process Communication (IPC)

Implementation of IPC using **Pipes**.

### Experiment 6 – Semaphore Implementation

Implementation of **Mutual Exclusion** using semaphores.

### Experiment 7 – Banker's Algorithm

Implementation of the **Banker's Algorithm** for deadlock avoidance.

### Experiment 8 – Deadlock Detection Algorithm

Implementation of an algorithm to detect deadlocks in a system.

### Experiment 9 – Threading

Multithreaded programs using **POSIX Threads (Pthreads)**.

### Experiment 10 – Paging Technique

Programs demonstrating paging and basic memory management concepts.

### Experiment 11 – Memory Allocation Methods

* First Fit
* Best Fit
* Worst Fit

### Experiment 12 – Page Replacement Algorithms

* FIFO
* LRU
* Optimal Page Replacement

### Experiment 13 – File Organization Techniques

* Sequential File Organization
* Direct File Organization
* Indexed File Organization

### Experiment 14 – File Allocation Strategies

* Sequential Allocation
* Indexed Allocation
* Linked Allocation

### Experiment 15 – Disk Scheduling Algorithms

* First Come First Serve (FCFS)
* Shortest Seek Time First (SSTF)
* SCAN
* C-SCAN

---

# 🚀 Beyond the Syllabus

The repository also includes additional projects for exploring operating system concepts in greater depth.

1. **Virtual Machine Performance Analyzer**
2. **CPU Scheduling Simulator**
3. **Memory Management Visualizer**
4. **Disk Scheduling Simulator**
5. **Virtualization in Cloud-Based AI Platforms**

---

# 📂 Folder Organization

Each experiment is organized into a separate folder:

```text
os-lab/
│
├── Exp1/
├── Exp2/
├── Exp3/
├── Exp4/
├── Exp5/
├── Exp6/
├── Exp7/
├── Exp8/
├── Exp9/
├── Exp10/
├── Exp11/
├── Exp12/
├── Exp13/
├── Exp14/
└── Exp15/
```

Each experiment folder contains separate `.c` and `.sh` files for the individual programs and sub-parts specified in the laboratory manual.

---

# ⚙️ How to Run

## Compiling and Running C Programs

Compile the program using `gcc`:

```bash
gcc filename.c -o output
```

Run the compiled program:

```bash
./output
```

### For Pthread Programs

Use the `-pthread` flag:

```bash
gcc filename.c -o output -pthread
./output
```

---

## Running Shell Scripts

First, make the script executable:

```bash
chmod +x filename.sh
```

Then run it:

```bash
./filename.sh
```

Alternatively:

```bash
bash filename.sh
```

---

# 🛠 Requirements

To run the programs, you will need:

* A Linux or UNIX-based operating system
* GCC Compiler
* Bash Shell
* POSIX Threads library for threading programs

On Ubuntu or Debian-based systems, GCC can be installed using:

```bash
sudo apt update
sudo apt install build-essential
```

---

# 📚 Topics Covered

This repository covers important Operating Systems concepts, including:

* UNIX Commands and Shell Programming
* Process Management
* System Calls
* CPU Scheduling
* Inter-Process Communication
* Semaphores and Synchronization
* Deadlocks
* Multithreading
* Memory Management
* Paging
* Page Replacement
* File Organization and Allocation
* Disk Scheduling
* Virtualization

---

## 📌 Note

These programs are intended for **educational and laboratory purposes**. The implementations are designed to demonstrate fundamental Operating System concepts and may be simplified for better understanding.

---

**Course:** CS5302 – Operating Systems Lab
**Institution:** Chennai Institute of Technology
