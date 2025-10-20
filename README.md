# Computer Science Master Roadmap (Software-Focused, with Essential Hardware)
**Track:** D1 (Software-Focused, Hardware-Lite)  
**Style:** S2 (Theory → Project)  
**Goal:** Understand computers from bare metal to operating systems, compilers, networking, and modern software systems.

---

## 🌍 Stage 0 — Prerequisites (1–2 weeks)
**You must be comfortable with:**
- Linux basics (Ubuntu recommended)
- Terminal & shell commands
- Git & GitHub
- VS Code + basic extensions

**Resources**
- "The Linux Command Line" (Book)
- YouTube: `Linux for Beginners`, `Git & GitHub Crash Course`

**Milestone Project**
- Host a GitHub repo and manage it via terminal

---

## ⚙️ Stage 1 — Foundations of Hardware (Lite) (2–4 weeks)
**Goal:** Understand how hardware runs software.

**Topics**
1. Binary, Decimal, Hex
2. Logic Gates (AND, OR, NOT, XOR)
3. Adders (Half/Full), ALU concept
4. Registers, Clock, Control Unit
5. CPU Execution Model (Fetch → Decode → Execute)
6. Memory Basics (RAM, Cache, Register difference)
7. Storage & Input/Output (simple overview)
8. x86-64 ISA Overview (concept only)

**Resources**
- Ben Eater (YouTube)
- Book: **But How Do It Know?** — J. Clark Scott

**Milestone Project**
- Build a *software simulation of a tiny CPU* (in Python or C)

---

## 🧠 Stage 2 — Machine Code & Assembly (4–6 weeks)
**Goal:** Understand how instructions run on x86-64 CPU.

**Topics**
1. What is an Instruction Set?
2. Registers (RAX, RBX, RCX…)
3. Stack, Stack Frames, Function Calls
4. Memory Addressing
5. Syscalls
6. Writing & running assembly on Linux

**Resources**
- `x86-64 Assembly - Intel Syntax` (YouTube)
- Book: **PC Assembly Language** — Paul Carter

**Milestone Project**
- Write assembly program that:
  - reads input
  - adds numbers
  - prints output (via syscall)

---

## 🧵 Stage 3 — C & Systems Programming (8–12 weeks)
**Goal:** Learn the language of operating systems.

**Topics**
1. Pointers, Memory Layout
2. Stack vs Heap
3. Static vs Dynamic Linking
4. Processes, fork(), exec()
5. Makefiles & GCC toolchain

**Resources**
- **C Programming Language — K&R**
- **Computer Systems: A Programmer’s Perspective (CSAPP)**

**Milestone Project**
- Write your own tiny shell (`sh`) in C

---

## 🗂️ Stage 4 — Operating Systems (10–16 weeks)
**Goal:** Understand how your OS manages everything.

**Topics**
1. Processes, Scheduling
2. Threads & Concurrency
3. Virtual Memory & Paging
4. File Systems (EXT4 concepts)
5. Device Drivers (concept level)
6. System Calls & Kernel/User Mode

**Resources**
- **Operating System Concepts — Galvin**
- **OSTEP (Free online)**

**Milestone Project**
- Write a tiny OS kernel that boots and prints to screen

---

## 🧰 Stage 5 — Computer Architecture (Software-Oriented)
**Goal:** Understand performance and CPU internals that impact software.

**Topics**
1. Caches (L1/L2/L3)
2. Pipelining
3. Branch Prediction
4. Out-of-order execution
5. NUMA (light)

**Milestone Project**
- Write C code to benchmark cache vs RAM speed

---

## 🧮 Stage 6 — Compilers & Interpreters (6–10 weeks)
**Goal:** See how your C/Python/JS turns into machine code.

**Topics**
1. Lexing → Parsing → AST
2. Code Generation
3. Optimization (basic)
4. Assembly Output

**Resources**
- “Crafting Interpreters”
- “Writing a C Compiler” tutorial series

**Milestone Project**
- Write a tiny programming language that compiles to assembly

---

## 🌐 Stage 7 — Computer Networks (8–12 weeks)
**Goal:** Understand the internet at a packet level.

**Topics**
1. TCP / UDP
2. IP, DNS, Routing
3. HTTP / HTTPS
4. Sockets Programming (in C or Python)

**Milestone Project**
- Build a simple HTTP server from scratch

---

## 🏛️ Stage 8 — Databases & Storage
**Goal:** Understand how data is stored and retrieved efficiently.

**Topics**
1. B-Trees, LSM Trees
2. Indexing
3. Transactions (ACID)
4. WAL (Write Ahead Log)

**Milestone Project**
- Build a tiny key-value store (like a baby LevelDB)

---

## 🐧 Stage 9 — Modern Software & OS Power User Skills
**Goal:** Become fluent in real-world systems.

**Topics**
- Linux internals
- Shell scripting
- Containers (Docker)
- Performance analysis tools
- Package managers
- System services

---

## 🧩 Final Mastery Projects (choose 1–2)
- Write your own *mini operating system*
- Write your own *mini compiler*
- Write your own *database engine*
- Write your own *network stack/server*

---

## ✅ After Finishing This Roadmap, You Will Be Able To:
- Understand computers from transistor → OS → network → application
- Read & write assembly
- Read kernel code
- Build low-level systems
- Debug like a pro
- Stand out as a **true systems engineer**

---

## 📌 Final Advice
Move slowly, finish one stage at a time, and **do every milestone project**.  
This is how you build *real understanding*, not just information.

---

