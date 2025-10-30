# Hi there, I'm Florin-Emanuel Bădilaș 👋

<p align="left">
  <a href="https://linkedin.com/in/badilas-florin-emanuel" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:badilasemi@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

## 👨‍💻 About Me

I'm a **Computer Science and Engineering** student at the **National University of Science and Technology POLITEHNICA Bucharest** (2023-2027).

I am deeply passionate about systems programming, operating systems, and network fundamentals. My projects are focused on understanding what happens "under the hood" — from building a custom `libc` with direct kernel syscalls and engineering a POSIX-compliant shell, to architecting compilers and low-level network clients from scratch.

---

## 🚀 My Tech Stack

### Core Languages & Technologies
<p align="left">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

### Currently Learning / Basic Knowledge
* Python, MATLAB, VHDL, Verilog, Haskell, Racket, Prolog

---

## 🔧 My Projects

Here are some of the key projects I've worked on.

### 1. [From Kernel to Userspace](https://github.com/FlorinBadilas/Mini-Libc) | C/C++
* Engineered a minimalistic, freestanding C standard library ("mini-libc") for Linux (x86_64), implementing critical functions by leveraging direct kernel system calls exclusively.
* Designed a custom memory allocator (malloc, free, realloc) from scratch, managing memory maps (mmap, munmap) and recreating core POSIX I/O primitives.

### 2. Mastering Process Control | C/C++ | (https://github.com/FlorinBadilas/Mini-Shell)
* Engineered a POSIX-compliant shell capable of process creation (fork, exec), complex I/O redirection (<, >, 2>), and piping (|) by managing raw file descriptors.
* Architected a robust parser to manage operator precedence (`|` > `&&` / `||` > `&` > `;`) and implemented short-circuit logic for conditional execution.

### 3. OOP Design Patterns in Practice | Java | (https://github.com/FlorinBadilas/Tourist-Application)
* Architected a data-centric backend using the **Singleton** pattern for centralized database state and **OOP inheritance** to model complex entities.
* Implemented an event-driven notification system (via the **Observer** pattern) and built a robust custom exception hierarchy.

### 4. Network Protocol Engineering | C/C++ | (https://github.com/FlorinBadilas/Web-Client)
* Developed a CLI client from the ground up, using raw TCP sockets to manually construct and transmit HTTP requests (GET, POST, DELETE) to a live RESTful API.
* Engineered robust client-side state management for JWT authentication (sending `Authorization` headers) and handled data serialization by building/parsing JSON payloads.

### 5. Deconstructing High-Level Logic | C/C++ | (https://github.com/FlorinBadilas/C-to-Asm-Compiler)
* Engineered a custom C-to-x86 transpiler, implementing a parser to map high-level arithmetic (MUL, DIV), logic (XOR), and shift (SHL) operations to raw assembly.
* Architected the complete control-flow logic, translating C-like `if-else` blocks and `for`/`while` loops into complex branching sequences using `CMP` and conditional jumps (`JNE`, `JGE`).

---

## 📈 My GitHub Stats

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=FlorinBadilas&show_icons=true&theme=tokyonight" alt="Florin Badilas's GitHub Stats" />
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=FlorinBadilas&layout=compact&theme=tokyonight" alt="Top Languages" />
</p>
