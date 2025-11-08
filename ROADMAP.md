# 🗺️ Assembly Learning Roadmap

A structured 16-week learning path for mastering Assembly language. This roadmap breaks down the comprehensive curriculum from [README.md](README.md) into manageable weekly study plans with clear objectives, tasks, and checkpoints.

## 📊 Quick Progress Tracker

Use this table to track your journey through the Assembly learning path:

| Level | Weeks | Lessons | Status |
|-------|-------|---------|--------|
| 🟢 Beginner | 1-4 | 1-8 | ⬜ Not Started |
| 🟡 Intermediate | 5-8 | 9-16 | ⬜ Not Started |
| 🟠 Advanced | 9-12 | 17-24 | ⬜ Not Started |
| 🔴 Expert | 13-16 | 25-32 | ⬜ Not Started |

**Legend:** ⬜ Not Started | 🟦 In Progress | ✅ Completed

---

## 📚 How to Use This Roadmap

### Getting Started
1. **Clone the repository** (if you haven't already):
   ```bash
   git clone https://github.com/sowngdp/assembly-learning.git
   cd assembly-learning
   ```

2. **Set up your environment** following the [Tools and Environment](README.md#tools-and-environment) section in README.md

3. **Follow the weekly plan** below, checking off items as you complete them

4. **Take your time** - This is a suggested pace. Feel free to adjust based on your schedule and learning speed

### Learning Tips 💡
- **Consistency over speed**: Daily 1-2 hour sessions are better than marathon sessions
- **Hands-on practice**: Type every code example yourself, don't just read
- **Debug everything**: Use debuggers to understand what's happening at each step
- **Take notes**: Keep a personal notebook of key concepts and "aha!" moments
- **Review regularly**: Spend time each week reviewing previous topics
- **Join the community**: Use GitHub Discussions for questions and sharing insights

### Getting Help 🆘
- **GitHub Issues**: Report errors in lessons or examples
- **GitHub Discussions**: Ask questions, share solutions, discuss concepts
- **Read error messages**: They often tell you exactly what's wrong
- **Consult README.md**: Detailed lesson descriptions and resources are there
- **External resources**: Don't hesitate to use books and videos mentioned in README.md

### Contributing Your Learning 🤝
- **Share solutions**: Post your exercise solutions in Discussions
- **Report issues**: Found a typo or bug? Open an issue
- **Suggest improvements**: Ideas for better examples? Open a PR
- **Help others**: Answer questions in Discussions when you can
- **Document your journey**: Share tips that helped you learn

---

## 🟢 Beginner Level (Weeks 1-4)

**Goal**: Build a solid foundation in Assembly language basics and write simple programs.

### Week 1: Introduction and First Steps

**Lessons**: 1-2 (Introduction to Assembly Language, Number Systems)

**Study Tasks** (5-7 hours):
- [ ] Read Lesson 1: Introduction to Assembly Language
- [ ] Read Lesson 2: Number Systems and Data Representation
- [ ] Watch video tutorials on CPU architecture
- [ ] Set up NASM and your chosen debugger

**Coding Tasks**:
- [ ] Install and verify NASM installation
- [ ] Practice binary to hexadecimal conversions (at least 20 examples)
- [ ] Practice two's complement representation (10 examples)
- [ ] Create a reference sheet for number conversions

**Review Checklist**:
- [ ] Can explain what Assembly language is and why it's useful
- [ ] Understand CPU architecture basics (registers, memory, ALU)
- [ ] Can convert between binary, hexadecimal, and decimal
- [ ] Understand signed vs. unsigned integers
- [ ] Know what two's complement is and how to calculate it

**Resources**: [README.md - About](README.md#about), [Prerequisites](README.md#prerequisites)

---

### Week 2: First Programs and Basic Operations

**Lessons**: 3-4 (First Assembly Program, Registers and Basic Operations)

**Study Tasks** (6-8 hours):
- [ ] Read Lesson 3: First Assembly Program
- [ ] Read Lesson 4: Registers and Basic Operations
- [ ] Study NASM syntax and program structure
- [ ] Learn about assembler and linker workflow

**Coding Tasks**:
- [ ] Write and run "Hello, World!" program
- [ ] Write a program that adds two numbers
- [ ] Write a program that subtracts two numbers
- [ ] Create a program using all general-purpose registers
- [ ] Experiment with INC and DEC operations

**Review Checklist**:
- [ ] Successfully compiled and ran first Assembly program
- [ ] Understand program structure (sections, labels, instructions)
- [ ] Know all general-purpose registers and their conventions
- [ ] Can use MOV instruction correctly
- [ ] Can perform basic arithmetic (ADD, SUB, INC, DEC)
- [ ] Understand the difference between registers and memory

**Resources**: [Getting Started](README.md#getting-started), [Tools and Environment](README.md#tools-and-environment)

---

### Week 3: Flags and Control Flow

**Lessons**: 5-6 (Flags and Conditional Operations, Control Flow - Jumps)

**Study Tasks** (6-8 hours):
- [ ] Read Lesson 5: Flags and Conditional Operations
- [ ] Read Lesson 6: Control Flow - Jumps
- [ ] Study how CPU flags work
- [ ] Learn about conditional jump instructions

**Coding Tasks**:
- [ ] Write a program that compares two numbers
- [ ] Implement simple if-else logic using conditional jumps
- [ ] Create a program that finds the maximum of two numbers
- [ ] Write a simple counting loop using jumps
- [ ] Debug a program step-by-step observing flag changes

**Review Checklist**:
- [ ] Understand all status flags (Zero, Carry, Sign, Overflow)
- [ ] Know how CMP and TEST instructions work
- [ ] Can use conditional jumps (JE, JNE, JG, JL, etc.)
- [ ] Can implement if-else logic in Assembly
- [ ] Can create simple loops with jumps
- [ ] Understand the difference between signed and unsigned comparisons

**Resources**: [Course Structure - Beginner Level](README.md#beginner-level)

---

### Week 4: Stack and Procedures

**Lessons**: 7-8 (The Stack, Procedures and Functions)

**Study Tasks** (7-9 hours):
- [ ] Read Lesson 7: The Stack
- [ ] Read Lesson 8: Procedures and Functions
- [ ] Study stack data structure and operations
- [ ] Learn about function calling conventions

**Coding Tasks**:
- [ ] Write a program demonstrating PUSH and POP
- [ ] Create a simple procedure that adds two numbers
- [ ] Write a function with parameters
- [ ] Implement a recursive function (factorial or fibonacci)
- [ ] Create a program with multiple function calls

**Review Checklist**:
- [ ] Understand stack structure (LIFO)
- [ ] Can use PUSH and POP correctly
- [ ] Know how ESP (stack pointer) works
- [ ] Can write procedures using CALL and RET
- [ ] Understand function prologue and epilogue
- [ ] Can pass parameters to functions
- [ ] Can create and use local variables

**Weekly Milestone**: You should now be able to write simple Assembly programs with functions and control flow!

**Resources**: [Beginner Level Lessons](README.md#beginner-level)

---

## 🟡 Intermediate Level (Weeks 5-8)

**Goal**: Master memory operations, data structures, and advanced programming techniques.

### Week 5: Memory Addressing and Arrays

**Lessons**: 9-10 (Memory Addressing Modes, Arrays and Strings)

**Study Tasks** (7-9 hours):
- [ ] Read Lesson 9: Memory Addressing Modes
- [ ] Read Lesson 10: Arrays and Strings
- [ ] Study effective address calculation
- [ ] Learn about string instructions

**Coding Tasks**:
- [ ] Write a program using different addressing modes
- [ ] Create and iterate through an array
- [ ] Implement array sum calculation
- [ ] Write a string copy function using MOVS
- [ ] Create a string comparison function

**Review Checklist**:
- [ ] Understand all addressing modes (immediate, register, direct, indirect, indexed)
- [ ] Can calculate effective addresses
- [ ] Can declare and access arrays
- [ ] Know string instructions (MOVS, CMPS, SCAS, STOS)
- [ ] Understand direction flag and REP prefix
- [ ] Can implement common array operations

**Resources**: [Intermediate Level Lessons](README.md#intermediate-level)

---

### Week 6: Bitwise Operations and Math

**Lessons**: 11-12 (Logical and Bitwise Operations, Multiplication and Division)

**Study Tasks** (7-9 hours):
- [ ] Read Lesson 11: Logical and Bitwise Operations
- [ ] Read Lesson 12: Multiplication and Division
- [ ] Study bit manipulation techniques
- [ ] Learn about shift and rotate operations

**Coding Tasks**:
- [ ] Write programs using AND, OR, XOR, NOT
- [ ] Create a bit masking example
- [ ] Implement multiplication using shifts
- [ ] Write division programs with DIV and IDIV
- [ ] Create a program that handles division overflow
- [ ] Implement a bit counting function

**Review Checklist**:
- [ ] Can use logical operations (AND, OR, XOR, NOT)
- [ ] Understand shift operations (SHL, SHR, SAL, SAR)
- [ ] Can use rotate operations (ROL, ROR, RCL, RCR)
- [ ] Know how to use MUL and IMUL
- [ ] Can handle DIV and IDIV operations
- [ ] Understand overflow handling
- [ ] Can optimize with bit operations

**Resources**: [Intermediate Level Lessons](README.md#intermediate-level)

---

### Week 7: Advanced Stack and Calling Conventions

**Lessons**: 13-14 (Advanced Stack Operations, Calling Conventions)

**Study Tasks** (7-9 hours):
- [ ] Read Lesson 13: Advanced Stack Operations
- [ ] Read Lesson 14: Calling Conventions
- [ ] Study different calling conventions
- [ ] Learn about interfacing with C/C++

**Coding Tasks**:
- [ ] Implement nested function calls
- [ ] Write functions following cdecl convention
- [ ] Write functions following stdcall convention
- [ ] Create an Assembly function callable from C
- [ ] Call a C function from Assembly
- [ ] Implement a variadic function

**Review Checklist**:
- [ ] Understand nested function calls
- [ ] Know register preservation rules
- [ ] Understand stack alignment requirements
- [ ] Can implement cdecl calling convention
- [ ] Can implement stdcall and fastcall conventions
- [ ] Can interface Assembly with C/C++
- [ ] Know stack cleanup responsibilities

**Resources**: [Intermediate Level Lessons](README.md#intermediate-level)

---

### Week 8: Macros and Debugging

**Lessons**: 15-16 (Macros and Conditional Assembly, Debugging Assembly Programs)

**Study Tasks** (7-9 hours):
- [ ] Read Lesson 15: Macros and Conditional Assembly
- [ ] Read Lesson 16: Debugging Assembly Programs
- [ ] Study macro definition and usage
- [ ] Master debugger usage (GDB/LLDB/WinDbg)

**Coding Tasks**:
- [ ] Create reusable macros for common operations
- [ ] Use conditional assembly directives
- [ ] Debug a complex program step-by-step
- [ ] Set breakpoints and inspect memory
- [ ] Find and fix intentional bugs in sample code
- [ ] Organize code using macros

**Review Checklist**:
- [ ] Can define and use macros
- [ ] Understand macro parameters
- [ ] Can use conditional assembly directives
- [ ] Proficient with debugger (breakpoints, stepping)
- [ ] Can inspect registers and memory during debugging
- [ ] Know common debugging strategies
- [ ] Can organize code effectively

**Weekly Milestone**: You can now write complex Assembly programs with proper structure and debug them effectively!

**Resources**: [Intermediate Level Lessons](README.md#intermediate-level), [Debuggers](README.md#debuggers)

---

## 🟠 Advanced Level (Weeks 9-12)

**Goal**: Master system-level programming, optimization, and advanced CPU features.

### Week 9: Floating-Point and SIMD

**Lessons**: 17-18 (Floating-Point Programming, SIMD Programming)

**Study Tasks** (8-10 hours):
- [ ] Read Lesson 17: Floating-Point Programming
- [ ] Read Lesson 18: SIMD Programming
- [ ] Study FPU architecture
- [ ] Learn about SSE/AVX extensions

**Coding Tasks**:
- [ ] Write a program using FPU instructions
- [ ] Implement floating-point arithmetic
- [ ] Create a SIMD program for parallel addition
- [ ] Write a vector multiplication program
- [ ] Benchmark SIMD vs. scalar operations

**Review Checklist**:
- [ ] Understand FPU architecture and registers
- [ ] Can use floating-point instructions
- [ ] Know SSE/AVX instructions
- [ ] Can implement SIMD operations
- [ ] Understand vector operations
- [ ] Can optimize with SIMD
- [ ] Know precision considerations

**Resources**: [Advanced Level Lessons](README.md#advanced-level)

---

### Week 10: System Calls and Memory Management

**Lessons**: 19-20 (System Calls, Memory Management)

**Study Tasks** (8-10 hours):
- [ ] Read Lesson 19: System Calls
- [ ] Read Lesson 20: Memory Management
- [ ] Study system call conventions (Linux/Windows)
- [ ] Learn about virtual memory

**Coding Tasks**:
- [ ] Write a file I/O program using system calls
- [ ] Create a program that allocates memory
- [ ] Implement read/write operations at system level
- [ ] Write a program demonstrating memory protection
- [ ] Create a simple memory allocator

**Review Checklist**:
- [ ] Can make system calls in Linux
- [ ] Can make system calls in Windows
- [ ] Know system call numbers and conventions
- [ ] Understand virtual memory concepts
- [ ] Know about page tables and address translation
- [ ] Can allocate and free memory
- [ ] Understand memory protection

**Resources**: [Advanced Level Lessons](README.md#advanced-level)

---

### Week 11: Interrupts and Multithreading

**Lessons**: 21-22 (Interrupts and Exceptions, Multithreading and Synchronization)

**Study Tasks** (8-10 hours):
- [ ] Read Lesson 21: Interrupts and Exceptions
- [ ] Read Lesson 22: Multithreading and Synchronization
- [ ] Study interrupt handling mechanisms
- [ ] Learn about atomic operations

**Coding Tasks**:
- [ ] Write an interrupt handler
- [ ] Create a multithreaded program
- [ ] Implement a spinlock
- [ ] Use atomic operations (LOCK prefix, XCHG)
- [ ] Create a thread-safe counter

**Review Checklist**:
- [ ] Understand interrupt handling
- [ ] Know exception types and handling
- [ ] Understand IDT (Interrupt Descriptor Table)
- [ ] Can create and manage threads
- [ ] Know atomic operations
- [ ] Can implement synchronization primitives
- [ ] Understand memory barriers

**Resources**: [Advanced Level Lessons](README.md#advanced-level)

---

### Week 12: Optimization and Position-Independent Code

**Lessons**: 23-24 (Performance Optimization, Position-Independent Code)

**Study Tasks** (8-10 hours):
- [ ] Read Lesson 23: Performance Optimization
- [ ] Read Lesson 24: Position-Independent Code (PIC)
- [ ] Study CPU pipeline and caching
- [ ] Learn about GOT and PLT

**Coding Tasks**:
- [ ] Profile and optimize a program
- [ ] Implement cache-friendly data structures
- [ ] Optimize branch-heavy code
- [ ] Write position-independent code
- [ ] Create a simple shared library

**Review Checklist**:
- [ ] Understand CPU pipeline and instruction scheduling
- [ ] Know cache optimization strategies
- [ ] Can optimize branch prediction
- [ ] Can profile and benchmark code
- [ ] Understand PIC requirements
- [ ] Know about GOT and PLT
- [ ] Can write relocatable code

**Weekly Milestone**: You can now write system-level programs and optimize them for performance!

**Resources**: [Advanced Level Lessons](README.md#advanced-level)

---

## 🔴 Expert Level (Weeks 13-16)

**Goal**: Master specialized topics and real-world applications of Assembly programming.

### Week 13: Reverse Engineering and Security

**Lessons**: 25-26 (Reverse Engineering Basics, Security Concepts)

**Study Tasks** (9-11 hours):
- [ ] Read Lesson 25: Reverse Engineering Basics
- [ ] Read Lesson 26: Security Concepts
- [ ] Study disassembly tools and techniques
- [ ] Learn about common vulnerabilities

**Coding Tasks**:
- [ ] Disassemble and analyze a simple program
- [ ] Identify compiler optimization patterns
- [ ] Create a buffer overflow demonstration (safely)
- [ ] Implement stack canary protection
- [ ] Study ROP chain construction
- [ ] Try challenges on Crackmes.one

**Review Checklist**:
- [ ] Can read disassembled code
- [ ] Can identify common patterns
- [ ] Understand compiler optimizations
- [ ] Know about buffer overflows
- [ ] Understand security mitigations (ASLR, DEP, NX)
- [ ] Know about stack canaries
- [ ] Understand ROP concepts

**Resources**: [Expert Level Lessons](README.md#expert-level), [Practice Platforms](README.md#practice-platforms)

---

### Week 14: Bootloaders and OS Concepts

**Lessons**: 27-28 (Bootloader Development, Operating System Concepts)

**Study Tasks** (9-11 hours):
- [ ] Read Lesson 27: Bootloader Development
- [ ] Read Lesson 28: Operating System Concepts
- [ ] Study BIOS and UEFI basics
- [ ] Learn about context switching

**Coding Tasks**:
- [ ] Write a simple bootloader
- [ ] Create a program demonstrating real mode
- [ ] Implement a basic task switcher
- [ ] Write a simple scheduler simulation
- [ ] Implement context save/restore

**Review Checklist**:
- [ ] Understand BIOS and UEFI basics
- [ ] Know real mode vs. protected mode
- [ ] Can write a simple bootloader
- [ ] Understand process/thread implementation
- [ ] Know how context switching works
- [ ] Can implement basic scheduling
- [ ] Understand system call implementation

**Resources**: [Expert Level Lessons](README.md#expert-level), [OSDev Wiki](https://wiki.osdev.org/)

---

### Week 15: Device Drivers and Cross-Platform

**Lessons**: 29-31 (Device Drivers, Inline Assembly, Cross-Platform Assembly)

**Study Tasks** (9-11 hours):
- [ ] Read Lesson 29: Device Drivers
- [ ] Read Lesson 30: Inline Assembly in C/C++
- [ ] Read Lesson 31: Cross-Platform Assembly
- [ ] Study I/O operations
- [ ] Learn about different architectures

**Coding Tasks**:
- [ ] Write simple I/O port operations
- [ ] Create a memory-mapped I/O example
- [ ] Write C code with inline Assembly (GCC)
- [ ] Write C code with inline Assembly (MSVC)
- [ ] Compare x86 and x64 code
- [ ] Study ARM assembly basics

**Review Checklist**:
- [ ] Can perform I/O port operations
- [ ] Understand memory-mapped I/O
- [ ] Can write inline Assembly in C/C++
- [ ] Know GCC and MSVC inline syntax
- [ ] Understand x86 vs. x64 differences
- [ ] Familiar with ARM assembly basics
- [ ] Know platform-specific considerations

**Resources**: [Expert Level Lessons](README.md#expert-level)

---

### Week 16: Final Project

**Lesson**: 32 (Final Project)

**Study Tasks** (10-15 hours):
- [ ] Read Lesson 32: Final Project
- [ ] Review all previous lessons
- [ ] Plan your final project
- [ ] Research best practices

**Project Tasks** (Choose one or create your own):
- [ ] Build a simple OS kernel
- [ ] Create a custom memory allocator
- [ ] Implement a cryptographic algorithm
- [ ] Build a small game or demo
- [ ] Create a system utility
- [ ] Develop an emulator or interpreter

**Project Requirements**:
- [ ] Uses concepts from at least 3 different levels
- [ ] Well-commented and documented
- [ ] Properly debugged and tested
- [ ] Optimized for performance
- [ ] Follows best practices

**Final Review Checklist**:
- [ ] Completed project meets requirements
- [ ] Code is clean and well-organized
- [ ] All concepts understood and applied
- [ ] Documented learning journey
- [ ] Shared project in repository Discussions
- [ ] Ready to help others learn

**Weekly Milestone**: Congratulations! You've completed the Assembly learning journey! 🎉

**Resources**: [Expert Level Lessons](README.md#expert-level), [Contributing](README.md#contributing)

---

## 🎯 After Completion

### Next Steps
- **Master a specific area**: Choose specialization (OS dev, security, optimization, etc.)
- **Contribute to open source**: Find Assembly projects on GitHub
- **Teach others**: Answer questions in Discussions, write tutorials
- **Stay current**: Follow processor architecture updates
- **Practice regularly**: Solve CTF challenges, reverse engineer programs

### Advanced Resources
- Read Intel and AMD architecture manuals in depth
- Study advanced OS development
- Learn about hardware-specific optimizations
- Explore embedded systems programming
- Study compiler design and implementation

### Community Contribution
- Share your final project
- Write about your learning experience
- Create additional exercises or lessons
- Help improve this roadmap
- Mentor new learners

---

## 📋 Weekly Time Commitment

**Recommended**: 7-11 hours per week
- **Study/Reading**: 3-4 hours
- **Coding/Practice**: 3-5 hours
- **Review/Debugging**: 1-2 hours

**Flexible Schedule**:
- Adjust based on your availability
- Quality over quantity
- Consistency is key
- Take breaks when needed

---

## ✅ Progress Tracking Tips

1. **Check off items** as you complete them in this roadmap
2. **Update the progress tracker table** at the top of this document
3. **Keep a learning journal** noting challenges and breakthroughs
4. **Mark your progress** in the Quick Progress Tracker table
5. **Celebrate milestones** at the end of each level
6. **Review regularly** - go back to previous weeks when needed

---

## 🤔 Frequently Asked Questions

**Q: What if I need more than one week for a topic?**
A: That's perfectly fine! This is a guide, not a race. Take the time you need to truly understand each concept.

**Q: Can I skip ahead to advanced topics?**
A: It's not recommended. Each level builds on previous knowledge. Skipping ahead might lead to confusion.

**Q: What if I get stuck?**
A: Use GitHub Discussions to ask questions, review the README.md for more details, consult external resources, or take a break and come back fresh.

**Q: Do I need to complete every single checkbox?**
A: The checklists ensure comprehensive learning. Try to complete them all, but focus on understanding over checkbox completion.

**Q: Can I work on multiple weeks simultaneously?**
A: It's better to focus on one week at a time to avoid overwhelming yourself and ensure solid understanding.

**Q: How do I know if I'm ready to move to the next level?**
A: Complete the weekly milestone projects and ensure you can answer the review checklist items confidently.

---

## 📞 Support and Community

- **Questions**: Use [GitHub Discussions](https://github.com/sowngdp/assembly-learning/discussions) for Q&A
- **Bugs/Issues**: Use [GitHub Issues](https://github.com/sowngdp/assembly-learning/issues) to report problems
- **Share Progress**: Post your achievements and projects in Discussions
- **Study Groups**: Consider forming study groups with other learners
- **Weekly Check-ins**: Share your weekly progress in Discussions

---

**Good luck on your Assembly learning journey! Remember: every expert was once a beginner. Stay curious, practice consistently, and don't hesitate to ask for help. You've got this! 💪🚀**
