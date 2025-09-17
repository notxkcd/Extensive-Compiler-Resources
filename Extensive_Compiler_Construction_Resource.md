# Extensive Compiler Construction Resource

This document is a curated collection of resources for learning about compiler construction, from introductory concepts to advanced topics. It aims to be a comprehensive guide for anyone interested in building, understanding, or working with compilers.

---

## Part 1: Foundations of Compiler Construction

### 1.1. Getting Started

#### Introductory Articles & Tutorials

*   [Let’s Build A Simple Interpreter](https://ruslanspivak.com/lsbasi-part1/)
*   [A Compiler Writing Journey](https://github.com/DoctorWkt/acwj)
*   [An Incremental Approach to Compiler Construction](http://scheme2006.cs.uchicago.edu/11-ghuloum.pdf)
*   [Let's Build a Teeny-Tiny Compiler](https://austinhenley.com/blog/teenytinycompiler1.html)
*   [Write a Compiler by Nora Sandler](https://norasandler.com/2017/11/29/Write-a-Compiler.html)
*   [Getting Started with Compilers](https://sbaziotis.com/compilers/getting-started-with-compilers.html)
*   [A Compiler Writing Journey by David A. Wheeler](https://www.dabeaz.com/compiler.html)
*   [Bootstrapping a simple compiler from nothing](https://archive.ph/cD1JK)
*   [Compiling to Assembly from Scratch](https://keleshev.com/compiling-to-assembly-from-scratch/)

#### Books for Beginners

*   [Crafting Interpreters by Bob Nystrom](http://craftinginterpreters.com/)
*   [Introduction to Compilers and Language Design by Douglas Thain](http://compilerbook.org/)
*   [The Compiler Book by Daniel Thain](https://www3.nd.edu/~dthain/compilerbook/)
*   [Compilerbook.com by Sam Author](https://compilerbook.com/)
*   [Interpreterbook.com by Sam Author](https://interpreterbook.com/)
*   [Let's Build a Compiler by Jack Crenshaw](https://compilers.iecc.com/crenshaw/)

### 1.2. Core Concepts

#### Lexing and Parsing

*   [Why we wrote yet another parser-compiler](https://www.sanity.io/blog/why-we-wrote-yet-another-parser-compiler)
*   [GCC Wiki: New C Parser](https://gcc.gnu.org/wiki/New_C_Parser)
*   [Parser Generators vs. Handwritten Parsers: A Survey of 2021](https://notes.eatonphil.com/parser-generators-vs-handwritten-parsers-survey-2021.html)

#### Abstract Syntax Trees (AST)

*   [AST in C++ Part 1: Variant](https://lesleylai.info/en/ast-in-cpp-part-1-variant/)

#### Intermediate Representation (IR)

*   [MLIR Rationale: Block Arguments vs. PHI Nodes](https://mlir.llvm.org/docs/Rationale/Rationale/#block-arguments-vs-phi-nodes)

#### Control Flow and Data Flow Analysis

*   [Notes on Graph Algorithms Used in Optimizing Compilers by Carl Offner](http://www.cs.umb.edu/~offner/files/flow_graph.pdf)

#### Static Single Assignment (SSA)

*   [Static Single Assignment (SSA) Book](https://github.com/pfalcon/ssabook)
*   [SSA-based Compiler Design](https://link.springer.com/book/9783030805142)

#### Optimization

*   [Compiler Optimization Options (GCC)](https://gcc.gnu.org/onlinedocs/gcc/Optimize-Options.html)
*   [Compiler Optimization Options (Clang)](http://clang.llvm.org/docs/CommandGuide/clang.html#cmdoption-O0)
*   [Compiler Optimization Options (Visual C++)](https://msdn.microsoft.com/en-us/library/19z1t1wy.aspx)
*   [Devirtualization in C++](https://hubicka.blogspot.com/search/label/devirtualization)
*   [Link time optimization (LTO)](https://hubicka.blogspot.com/search/label/link-time%20optimization)
*   [Optimizations in C++ Compilers: A practical journey by Matt Godbolt](https://queue.acm.org/detail.cfm?id=3372264)

#### Instruction Selection

*   [Instruction Selection: Principles, Methods, & Applications](http://kth.diva-portal.org/smash/record.jsf?pid=diva2:951540)
*   [Universal Instruction Selection](http://www.diva-portal.org/smash/record.jsf?pid=diva2:1185339)

#### Linking and Loading

*   [Linking and Loading](https://github.com/MattPD/cpplinks/blob/master/executables.linking_loading.md)

---

## Part 2: Platforms, Toolchains, and Languages

### 2.1. LLVM

*   [LLVM Homepage](http://llvm.org/)
*   [A Tourist’s Guide to the LLVM Source Code](http://blog.regehr.org/archives/1453)
*   [How Clang Compiles a Function](https://blog.regehr.org/archives/1605)
*   [How LLVM Optimizes a Function](https://blog.regehr.org/archives/1603)
*   [Life of an instruction in LLVM](http://eli.thegreenplace.net/2012/11/24/life-of-an-instruction-in-llvm)
*   [LLVM Tutorial: Kaleidoscope](http://llvm.org/docs/tutorial/)
*   [LLVM for Grad Students](http://adriansampson.net/blog/llvm.html)
*   [Testing LLVM](http://blog.regehr.org/archives/1450)
*   [Tutorial: Creating an LLVM Backend for the Cpu0 Architecture](https://jonathan2251.github.io/lbd/)
*   [Tutorial: Creating an LLVM Toolchain for the Cpu0 Architecture](http://jonathan2251.github.io/lbt/)

### 2.2. GCC

*   [GCC Homepage](https://gcc.gnu.org/)
*   [GCC Wiki](https://gcc.gnu.org/wiki)
*   [GCC online documentation](https://gcc.gnu.org/onlinedocs/)

### 2.3. JVM (Java Virtual Machine)

#### JVM Internals & Architecture

*   [Java Code to Byte Code: Part 1](https://blog.jamesdbloom.com/JavaCodeToByteCode_PartOne.html)
*   [How Bytecodes are Interpreted by JVM](https://jugbd.org/how-byte-codes-are-interpreted-by-jvm/)
*   [Bending the Rules with Java Bytecode](https://www.infoq.com/articles/Java-Bytecode-Bending-the-Rules/)
*   [Recaf Bytecode Documentation](https://www.coley.software/Recaf-documentation/use-bytecode-list.html)
*   [Which bytecode instructions are considered to be "wide"?](https://www.reddit.com/r/java/comments/15aafuz/which_byte_code_instructions_are_considered_to_be/)
*   [A Java Programmer's Guide to Bytecode](https://www.beyondjava.net/java-programmers-guide-java-byte-code)
*   [Java Bytecode Tutorial](https://www.jrebel.com/blog/java-bytecode-tutorial)
*   [An Introduction to JVM Bytecode](https://medium.com/swlh/an-introduction-to-jvm-bytecode-5ef3165fae70)
*   [JVM Bytecode Instructions Explained](https://medium.com/@nataliiadziubenko/jvm-bytecode-instructions-explained-41a3764dd141)
*   [An Introduction to Java Bytecode](https://medium.com/@AlexanderObregon/an-introduction-to-java-bytecode-885677548674)
*   [Introduction to Java Bytecode](https://dzone.com/articles/introduction-to-java-bytecode)
*   [Understanding Java Byte Code](https://stackoverflow.com/questions/1552308/understanding-java-byte-code)
*   [The Java Virtual Machine Specification, Java SE 7 Edition: Chapter 4](https://docs.oracle.com/javase/specs/jvms/se7/html/jvms-4.html)
*   [The Java Virtual Machine Specification, Java SE 7 Edition: Chapter 6](https://docs.oracle.com/javase/specs/jvms/se7/html/jvms-6.html)

#### JVM Tools

*   [Decompilers](#decompilers)
*   [Assemblers and Disassemblers](#assemblers-and-disassemblers)
*   [Bytecode Engineering Libraries](#bytecode-engineering-libraries)
*   [Debugging and Profiling Tools](#debugging-and-profiling-tools)

#### JVM-Based Compiler Projects

*   [Tiny Java Compiler](https://github.com/hehez/Tiny-Java-Compiler)
*   [MiniJava Compiler (JavaCC)](https://github.com/BlackyDrum/mini-java-compiler)
*   [Extended MiniJava Compiler (JFlex + Jasmin)](https://github.com/bhavinshah7/Mini-Java-Compiler)
*   [C/C++ Mini-Java Compiler](https://github.com/greati/mini-java-compiler)
*   [TinyJ](https://github.com/harry1357931/TinyJava-ParseTree-Compiler-execute_VMcode)
*   [Java-based MiniJava to LLVM](https://github.com/vsakkas/minijava-compiler)
*   [tinyjava](https://github.com/arturo182/tinyjava)

#### Alternative JVMs

*   [Jikes RVM](https://github.com/JikesRVM/JikesRVM)
*   [Maxine VM](https://github.com/beehive-lab/Maxine-VM)
*   [Cacao JVM](http://www.cacaovm.org/)
*   [GraalVM](https://www.graalvm.org/)
*   [JamVM](https://jamvm.sourceforge.net/)
*   [TakaTuka](https://en.wikipedia.org/wiki/TakaTuka)
*   [PreonVM](https://en.m.wikipedia.org/wiki/PreonVM)
*   [IKVM.NET](https://en.m.wikipedia.org/wiki/IKVM)
*   [LeJOS](https://en.m.wikipedia.org/wiki/LeJOS)
*   [NanoVM](http://harbaum.org/till/nanovm/index.shtml)
*   [Mika VM](https://en.m.wikipedia.org/wiki/Mika_VM)
*   [Kaffe](http://www.kaffe.org/)

### 2.4. C++ Compilers

*   [C++ Compiler Resources](#c-compiler-resources)

### 2.5. Other Languages and Compilers

#### Forth

*   [JonesForth](https://github.com/phf/forth)

#### J

*   [J Programming Language](https://www.cs.umb.edu/j--/)

#### Oberon

*   [Wirth's Home Page](https://people.inf.ethz.ch/wirth/index.html)
*   [Wirth's Compiler Page with code](https://people.inf.ethz.ch/wirth/CompilerConstruction/)
*   [Project Oberon](https://web.archive.org/web/20230120051556/http://www.projectoberon.com/)
*   [Project Oberon (Archive)](https://archive.ph/2lMca)
*   [Active Oberon](http://oberon2005.oberoncore.ru/paper/p_ao.pdf)
*   [Oberon Language Report](https://people.inf.ethz.ch/wirth/Oberon/Oberon.Report.pdf)
*   [Oberon Emulator](https://github.com/schierlm/OberonEmulator)
*   [oberonc](https://github.com/lboasso/oberonc)
*   [The School of Niklaus Wirth: The Art of Simplicity](http://pascal.hansotten.com/niklaus-wirth/school-of-wirth/)

#### Pascal

*   [Free Pascal](https://www.freepascal.org/)
*   [Turbo Pascal Compiler](https://turbopascal.org/compiler)

#### K Lang

*   [Shakti K Education](https://shakti.com/edu)
*   [K Book](https://xpqz.github.io/kbook/Introduction.html)
*   [ksimple GitHub](https://github.com/kparc/ksimple)
*   [Hacker News Discussion 1](https://news.ycombinator.com/item?id=39026551)
*   [Hacker News Discussion 2](https://news.ycombinator.com/item?id=38868574)

#### T3X

*   [T3X Language](http://t3x.org/t3x/book.html)
*   [T3X Reloaded](http://t3x.org/reload/index.html)

---

## Part 3: Advanced Topics

### 3.1. Virtual Machines

*   [Metacircular Virtual Machines](https://www.steveblackburn.org/pubs/papers/vmmagic-vee-2009.pdf)
*   [A Concise and Opinionated History of Virtual Machines](https://archive.org/download/vmss16/wolczko.pdf)

### 3.2. Garbage Collection

*   [Understanding the Java Virtual Machine: Memory Management (Pluralsight)](https://www.pluralsight.com/courses/understanding-java-vm-memory-management)
*   [7 Best Courses to Learn JVM Garbage Collection and Performance Tuning](https://medium.com/javarevisited/7-best-courses-to-learn-jvm-garbage-collection-and-performance-tuning-for-experienced-java-331705180686)

### 3.3. Superoptimization

*   [GNU Superoptimizer Version 2](https://github.com/embecosm/gso2)
*   [Souper - a superoptimizer for LLVM IR](https://github.com/google/souper)
*   [Stochastic Superoptimization](http://blog.regehr.org/archives/923)
*   [STOKE: A stochastic superoptimizer and program synthesizer](http://stoke.stanford.edu)

### 3.4. Code Obfuscation

*   [The International Obfuscated C Code Contest (IOCCC)](https://en.m.wikipedia.org/wiki/International_Obfuscated_C_Code_Contest)

---

## Part 4: Learning Resources

### 4.1. Books

*   [List of Compiler Books (GCC Wiki)](https://gcc.gnu.org/wiki/ListOfCompilerBooks)
*   [Essentials of Compilation: An Incremental Approach](https://github.com/IUCompilerCourse/Essentials-of-Compilation)
*   [Essentials of Compilation (MIT Press)](https://mitpress.mit.edu/9780262047760/essentials-of-compilation/)

### 4.2. Courses

*   [Cornell CS 6120: Advanced Compilers](https://www.cs.cornell.edu/courses/cs6120/2020fa/)
*   [IIT Delhi COL874: Advanced Compiler Techniques](https://iitd.github.io/col874/)
*   [IU P423/P523: Compilers (Programming Language Implementation)](https://iucompilercourse.github.io/IU-P423-P523-E313-E513-Fall-2020/)
*   [KAIST CS420: Compiler Design](https://github.com/kaist-cp/cs420)
*   [Stanford OpenEdX: Compilers](http://online.stanford.edu/course/compilers-0)
*   [UCSD CSE 131: Compiler Construction](https://ucsd-cse131-f19.github.io/)

### 4.3. Talks and Videos

*   [Anders Hejlsberg on Modern Compiler Construction](https://learn.microsoft.com/en-us/shows/seth-juarez/anders-hejlsberg-on-modern-compiler-construction)
*   [Understanding Compiler Optimization by Chandler Carruth](https://www.youtube.com/watch?v=FnGCDLhaxKU)
*   [An overview of Clang](https://www.youtube.com/watch?v=5kkMpJpIGYU)
*   [Introduction to LLVM](https://www.youtube.com/watch?v=J5xExRGaIIY)
*   [Natalie Language](https://www.youtube.com/playlist?list=PLWUx_XkUoGTq-nkbhnk6PN4m109ISo5BX)
*   [Jakt Language Hacking](https://www.youtube.com/watch?v=3RO1Jtve6v8&list=PLMOpZvQB55bf2J-TgMOejaViKhN_VkPdE)
*   [JS Bytecode VM](https://www.youtube.com/playlist?list=PLMOpZvQB55beChggmvk-sUm8X_vSezpqL)

### 4.4. Blogs and Websites

*   [awesome-compilers](https://github.com/aalhour/awesome-compilers)
*   [The LLVM Blog](http://blog.llvm.org/)
*   [John Regehr's Blog](http://blog.regehr.org/)
*   [The Old New Thing](https://devblogs.microsoft.com/oldnewthing/)
*   [CS 6120 Blog](https://www.cs.cornell.edu/courses/cs6120/2020fa/blog/)
*   [Tagless Final Compiler](https://okmij.org/ftp/tagless-final/Compiler/index.html)
*   [Alarming Development](https://alarmingdevelopment.org/?p=805)
*   [The Holub series on compilers](https://holub.com/compiler/)
*   [Federico Tomassetti's Resources to Create Programming Languages](https://tomassetti.me/resources-create-programming-languages/)
*   [Create Your Own Programming Language](http://createyourproglang.com/)

### 4.5. Tools

*   [ANTLR](https://www.antlr.org/)
*   [QBE Backend](https://c9x.me/compile/)
*   [Tiny C Compiler](https://bellard.org/tcc/)

### 4.6. Conferences

*   [ASPLOS](https://asplos-conference.org/)
*   [CGO](http://cgo.org/)
*   [PLDI](http://www.sigplan.org/Conferences/PLDI/)
*   [POPL](http://www.sigplan.org/Conferences/POPL/)

### 4.7. Other Notable Resource Collections (Inspiration for this)

*   [Compilers and Interpreters by Phil Eaton](https://eatonphil.com/compilers-and-interpreters.html)
*   [Programming Language Resources by Bernstein Bear](https://bernsteinbear.com/pl-resources/)
*   [Resources for Amateur Compiler Writers](http://c9x.me/compile/bib/)
