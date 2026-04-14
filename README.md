# Linux OS Internals & System Programming Portfolio

Welcome to my 2025 Operating System project collection. This repository serves as an index for a series of advanced system programming projects, focusing on Linux kernel modules, process management, concurrency, and virtual file systems.

### Tech Stack
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GCC](https://img.shields.io/badge/GCC-A100FF?style=for-the-badge&logo=gnu&logoColor=white)

---

## Project Index

Click on the project titles below to navigate to the respective repositories for source code and detailed documentation.

### 1. [In-Memory File System (OSFS)](https://github.com/pukyle/OS_2025_File_System)
* **Topics:** Virtual File System (VFS), Kernel Module, Memory Management
* **Description:** Designed and implemented a custom in-memory file system. Explored the Linux VFS layer to handle inode creation, directory traversal, and file operations strictly within RAM, demonstrating an understanding of kernel-space memory allocation.

### 2. [Custom Linux Shell](https://github.com/pukyle/OS_2025_Shell)
* **Topics:** Process Control, System Calls (`fork`, `exec`, `wait`), File Descriptors
* **Description:** Built a command-line interpreter from scratch in C. The shell supports core functionalities including execution of built-in commands, foreground/background process management, input/output redirection, and inter-process piping.

### 3. [Multithreading & Synchronization LKM](https://github.com/pukyle/OS_2025_Multithreading_LKM)
* **Topics:** Concurrency, Thread Synchronization, Custom Spinlocks, x86 Assembly
* **Description:** Developed a Linux Kernel Module (LKM) to demonstrate multithreading in kernel space. Implemented and benchmarked concurrency control mechanisms, including custom spinlocks utilizing atomic x86 assembly instructions to prevent race conditions.

### 4. [Inter-Process Communication (IPC)](https://github.com/pukyle/OS_2025_IPC)
* **Topics:** IPC Mechanisms, Shared Memory, Message Queues, POSIX Threads
* **Description:** Engineered robust communication channels between isolated processes. Evaluated the performance and architectural trade-offs of different IPC models (e.g., pipes, shared memory) to achieve efficient data synchronization and task coordination.

---
*Created by Cheng-Yu Pu, 2025.*
