# Assembly Learning

A comprehensive guide to learning Assembly language from beginner to advanced level. This repository provides structured lessons, examples, and exercises to help you master low-level programming.

## 📚 Table of Contents

- [About](#about)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Learning Path](#learning-path)
- [Course Structure](#course-structure)
- [Tools and Environment](#tools-and-environment)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

## 🎯 About

This repository is designed to guide you through learning Assembly language from the ground up. Whether you're a complete beginner or looking to deepen your understanding of low-level programming, you'll find structured lessons that progressively build your skills.

Assembly language is the closest human-readable representation of machine code and provides invaluable insights into:
- How computers actually work at the hardware level
- Memory management and CPU operations
- Performance optimization
- Reverse engineering and security analysis
- Operating system internals

## ✅ Prerequisites

Before starting this course, you should have:
- Basic understanding of programming concepts (variables, loops, conditionals)
- Familiarity with number systems (binary, hexadecimal)
- A computer running Windows, Linux, or macOS
- Patience and curiosity to learn low-level concepts

## 🚀 Getting Started

1. Clone this repository:
```bash
git clone https://github.com/sowngdp/assembly-learning.git
cd assembly-learning
```

2. Set up your development environment (see [Tools and Environment](#tools-and-environment))

3. Start with Lesson 1 in the `lessons/` directory

4. Follow the lessons in order, completing exercises before moving forward

## 📖 Learning Path

The course is divided into four main levels:

### 🟢 **Beginner Level** (Weeks 1-4)
Foundation concepts and basic programming

### 🟡 **Intermediate Level** (Weeks 5-8)
Working with data structures and advanced instructions

### 🟠 **Advanced Level** (Weeks 9-12)
System-level programming and optimization

### 🔴 **Expert Level** (Weeks 13-16)
Specialized topics and real-world applications

## 📋 Course Structure

### **Beginner Level**

#### Lesson 1: Introduction to Assembly Language
- What is Assembly language?
- CPU architecture basics (registers, memory, ALU)
- Assembly vs. high-level languages
- Setting up your environment

#### Lesson 2: Number Systems and Data Representation
- Binary, hexadecimal, and octal systems
- Signed and unsigned integers
- Two's complement representation
- Converting between number systems

#### Lesson 3: First Assembly Program
- Writing "Hello, World!" in Assembly
- Understanding the assembler and linker
- Program structure and syntax
- Comments and code organization

#### Lesson 4: Registers and Basic Operations
- General-purpose registers (EAX, EBX, ECX, EDX)
- Special-purpose registers (ESP, EBP, EIP)
- MOV instruction and data movement
- Basic arithmetic operations (ADD, SUB, INC, DEC)

#### Lesson 5: Flags and Conditional Operations
- Status flags (Zero, Carry, Sign, Overflow)
- Comparison operations (CMP, TEST)
- Understanding how flags are set
- Basic conditional logic

#### Lesson 6: Control Flow - Jumps
- Unconditional jumps (JMP)
- Conditional jumps (JE, JNE, JG, JL, etc.)
- Creating simple if-else logic
- Loop basics with jumps

#### Lesson 7: The Stack
- Stack structure and operations
- PUSH and POP instructions
- Stack pointer (ESP) management
- Stack frames basics

#### Lesson 8: Procedures and Functions
- CALL and RET instructions
- Function prologue and epilogue
- Parameter passing conventions
- Local variables

---

### **Intermediate Level**

#### Lesson 9: Memory Addressing Modes
- Immediate, register, and direct addressing
- Indirect and indexed addressing
- Base+offset addressing
- Effective address calculation

#### Lesson 10: Arrays and Strings
- Declaring and accessing arrays
- String operations (MOVS, CMPS, SCAS, STOS)
- Direction flag and REP prefix
- Implementing string functions

#### Lesson 11: Logical and Bitwise Operations
- AND, OR, XOR, NOT operations
- Shift operations (SHL, SHR, SAL, SAR)
- Rotate operations (ROL, ROR, RCL, RCR)
- Bit manipulation techniques

#### Lesson 12: Multiplication and Division
- MUL and IMUL instructions
- DIV and IDIV instructions
- Handling overflow
- Optimizing with shifts

#### Lesson 13: Advanced Stack Operations
- Nested function calls
- Preserving registers
- Stack alignment
- Variable argument functions

#### Lesson 14: Calling Conventions
- cdecl, stdcall, fastcall
- Stack cleanup responsibilities
- Register preservation rules
- Interfacing with C/C++

#### Lesson 15: Macros and Conditional Assembly
- Defining and using macros
- Macro parameters
- Conditional assembly directives
- Code organization techniques

#### Lesson 16: Debugging Assembly Programs
- Using debuggers (GDB, LLDB, WinDbg)
- Setting breakpoints
- Inspecting registers and memory
- Common debugging strategies

---

### **Advanced Level**

#### Lesson 17: Floating-Point Programming
- FPU architecture and registers
- Floating-point instructions
- SSE/AVX instructions
- Precision and performance considerations

#### Lesson 18: SIMD Programming
- MMX, SSE, and AVX extensions
- Parallel data processing
- Vector operations
- Performance optimization with SIMD

#### Lesson 19: System Calls
- Making system calls in Linux
- Making system calls in Windows
- System call numbers and conventions
- File I/O at the system level

#### Lesson 20: Memory Management
- Virtual memory concepts
- Page tables and address translation
- Memory protection
- Allocating and freeing memory

#### Lesson 21: Interrupts and Exceptions
- Interrupt handling
- Exception types and handling
- Interrupt descriptor table (IDT)
- Hardware vs. software interrupts

#### Lesson 22: Multithreading and Synchronization
- Thread creation and management
- Atomic operations (LOCK prefix, XCHG, CMPXCHG)
- Spinlocks and mutexes
- Memory barriers and ordering

#### Lesson 23: Performance Optimization
- CPU pipeline and instruction scheduling
- Cache optimization strategies
- Branch prediction optimization
- Profiling and benchmarking

#### Lesson 24: Position-Independent Code (PIC)
- Understanding PIC requirements
- Global Offset Table (GOT)
- Procedure Linkage Table (PLT)
- Writing relocatable code

---

### **Expert Level**

#### Lesson 25: Reverse Engineering Basics
- Reading disassembled code
- Identifying common patterns
- Understanding compiler optimizations
- Tools and techniques

#### Lesson 26: Security Concepts
- Buffer overflows
- Stack canaries and protections
- Return-oriented programming (ROP)
- Security mitigations (ASLR, DEP, NX)

#### Lesson 27: Bootloader Development
- BIOS and UEFI basics
- Real mode vs. protected mode
- Writing a simple bootloader
- Loading and executing code

#### Lesson 28: Operating System Concepts
- Process and thread implementation
- Context switching
- System call implementation
- Scheduler basics

#### Lesson 29: Device Drivers
- I/O port operations
- Memory-mapped I/O
- Interrupt handling in drivers
- Simple driver example

#### Lesson 30: Inline Assembly in C/C++
- GCC inline assembly syntax
- MSVC inline assembly syntax
- Constraints and clobbers
- Optimizing critical sections

#### Lesson 31: Cross-Platform Assembly
- x86 vs. x64 differences
- ARM assembly basics
- Platform-specific considerations
- Portable assembly techniques

#### Lesson 32: Final Project
- Applying all learned concepts
- Building a complete application
- Code review and optimization
- Best practices and next steps

## 🛠️ Tools and Environment

### Assemblers
- **NASM** (Netwide Assembler) - Recommended for beginners
- **MASM** (Microsoft Macro Assembler) - For Windows development
- **GAS** (GNU Assembler) - For Linux/Unix systems
- **FASM** (Flat Assembler) - Lightweight and fast

### Debuggers
- **GDB** (GNU Debugger) - Linux/Unix
- **LLDB** - macOS and modern systems
- **WinDbg** - Windows
- **x64dbg** - Windows, user-friendly interface
- **Radare2** - Cross-platform reverse engineering

### IDEs and Editors
- **Visual Studio** - Full IDE with debugging support
- **VS Code** with Assembly extensions
- **SASM** - Simple crossplatform IDE for NASM, MASM, GAS
- **Vim/Emacs** with syntax highlighting

### Virtual Machines (Recommended)
- **VirtualBox** - For safe experimentation
- **VMware** - Professional virtualization
- **QEMU** - For low-level development

### Installation Guides

#### Linux (Ubuntu/Debian):
```bash
sudo apt-get update
sudo apt-get install nasm gdb build-essential
```

#### macOS:
```bash
brew install nasm
```

#### Windows:
- Download NASM from: https://www.nasm.us/
- Install Visual Studio for MASM
- Use WSL (Windows Subsystem for Linux) for Linux-like environment

## 📚 Resources

### Books
- "Programming from the Ground Up" by Jonathan Bartlett
- "Assembly Language Step-by-Step" by Jeff Duntemann
- "The Art of Assembly Language" by Randall Hyde
- "Professional Assembly Language" by Richard Blum

### Online Resources
- [Intel® 64 and IA-32 Architectures Software Developer Manuals](https://software.intel.com/content/www/us/en/develop/articles/intel-sdm.html)
- [AMD Developer Guides](https://developer.amd.com/resources/developer-guides-manuals/)
- [NASM Documentation](https://www.nasm.us/docs.php)
- [OSDev Wiki](https://wiki.osdev.org/)

### Video Tutorials
- University lectures on computer architecture
- YouTube channels focused on low-level programming
- Assembly programming conference talks

### Practice Platforms
- [Crackmes.one](https://crackmes.one/) - Reverse engineering challenges
- [Microcorruption](https://microcorruption.com/) - Embedded security CTF
- [pwnable.kr](http://pwnable.kr/) - Security wargames

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute to this learning repository:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-lesson`)
3. Commit your changes (`git commit -m 'Add new lesson on topic'`)
4. Push to the branch (`git push origin feature/new-lesson`)
5. Open a Pull Request

### Contribution Guidelines
- Follow the existing lesson structure and format
- Include practical examples and exercises
- Test all code examples before submitting
- Add comments explaining complex concepts
- Update this README if adding new sections

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Thanks to all contributors who help improve this learning resource
- Inspired by the Assembly programming community
- Special thanks to educators making low-level programming accessible

---

## 📞 Contact & Support

- **Issues**: Please use the GitHub issue tracker for bugs or questions
- **Discussions**: Join our discussions for Q&A and community support
- **Updates**: Watch this repository for new lessons and improvements

---

**Happy Learning! 🎉**

Remember: Assembly might seem challenging at first, but with practice and patience, you'll gain deep insights into how computers work. Take it one lesson at a time, experiment with the code, and don't hesitate to ask questions!
