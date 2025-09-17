# Compiler and JVM Resources

This document contains a curated list of resources for learning about compiler construction, the Java Virtual Machine (JVM), and related topics.

## General Compiler Construction

*   [Compiler Construction Book](https://dthain.github.io/books/compiler/)
*   [The Compiler Book by Daniel Thain](https://www3.nd.edu/~dthain/compilerbook/)
*   [Compilerbook.com by Sam Author](https://compilerbook.com/)
*   [Interpreterbook.com by Sam Author](https://interpreterbook.com/)
*   [Let's Build a Compiler by Jack Crenshaw](https://compilers.iecc.com/crenshaw/)
*   [Hacker News: Compiler Construction](https://news.ycombinator.com/item?id=36102865)
*   [Hacker News: Another Compiler Discussion](https://news.ycombinator.com/item?id=38331042)
*   [Cognitive Load in Programming](https://github.com/zakirullin/cognitive-load)
*   [An Incremental Approach to Compiler Construction](http://scheme2006.cs.uchicago.edu/11-ghuloum.pdf)
*   [Essentials of Compilation: An Incremental Approach in Racket by Jeremy G. Siek](https://github.com/IUCompilerCourse/Essentials-of-Compilation)
*   [Let's Build a Teeny-Tiny Compiler](https://austinhenley.com/blog/teenytinycompiler1.html)
*   [Modern Compiler Implementation in C](https://www.cs.princeton.edu/~appel/modern/)
*   [Lisp: My Second Attempt at Explaining Interpreters](https://returnzero.win/2023/01/28/lisp-my-second-attempt-at-explaining-interpreters/)
*   [Metacircular Virtual Machines](https://www.steveblackburn.org/pubs/papers/vmmagic-vee-2009.pdf)
*   [Programming Languages: Application and Interpretation](https://cs.brown.edu/courses/cs173/2012/book/)
*   [Write You a Haskell](https://smunix.github.io/dev.stephendiehl.com/fun/index.html)
*   [My Computing Story](https://austinhenley.com/blog/mycomputingstory.html)
*   [Cfront 3.0.3](https://github.com/mingodad/cfront-3)
*   [Cfront 1.2](https://github.com/seyko2/cfront-1)
*   [Programming Language Resources](https://bernsteinbear.com/pl-resources/)
*   [Why we wrote yet another parser-compiler](https://www.sanity.io/blog/why-we-wrote-yet-another-parser-compiler)
*   [Compiling to Assembly from Scratch](https://keleshev.com/compiling-to-assembly-from-scratch/)
*   [Write a Compiler by Nora Sandler](https://norasandler.com/2017/11/29/Write-a-Compiler.html)
*   [Getting Started with Compilers](https://sbaziotis.com/compilers/getting-started-with-compilers.html)
*   [A Compiler Writing Journey by David A. Wheeler](https://www.dabeaz.com/compiler.html)

## Resource Collections
*   [Compilers and Interpreters by Phil Eaton](https://eatonphil.com/compilers-and-interpreters.html)
*   [Programming Language Resources by Bernstein Bear](https://bernsteinbear.com/pl-resources/)
*   [Resources for Amateur Compiler Writers](https://c9x.me/compile/bib/)

## JVM Internals and Architecture

### Bytecode

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

### Memory Management

*   [Understanding the Java Virtual Machine: Memory Management (Pluralsight)](https://www.pluralsight.com/courses/understanding-java-vm-memory-management)
*   [7 Best Courses to Learn JVM Garbage Collection and Performance Tuning](https://medium.com/javarevisited/7-best-courses-to-learn-jvm-garbage-collection-and-performance-tuning-for-experienced-java-331705180686)
*   [Java Memory Management Explained (DigitalOcean)](https://www.digitalocean.com/community/tutorials/java-jvm-memory-model-memory-management-in-java)
*   [Java Memory Management (GeeksforGeeks)](https://www.geeksforgeeks.org/java/java-memory-management/)
*   [Java Stack and Heap (Baeldung)](https://www.baeldung.com/java-stack-heap)
*   [How the Java virtual machine handles exceptions](https://www.infoworld.com/article/2165977/how-the-java-virtual-machine-handles-exceptions.html)
*   [mmap(2) - Linux manual page](https://man7.org/linux/man-pages/man2/mmap.2.html)
*   [Rhizome Memory Management](https://github.com/chrisseaton/rhizome/blob/main/doc/memory.md)
*   [RhizomeRuby Memory](https://github.com/chrisseaton/rhizome/blob/main/lib/rhizomeruby/memory.rb#L72)
*   [Rhizome](https://github.com/chrisseaton/rhizome)

## JVM Tools

### Decompilers

*   **JD-GUI:** Classic GUI decompiler.
*   **CFR:** Modern, well-maintained decompiler.
*   **Procyon:** Good for Java 8+ features like lambdas.
*   **FernFlower:** IntelliJ’s built-in decompiler.
*   **JADX:** Mainly for Android DEX → Java, but works for JVM too.
*   **Bytecode-Viewer:** Combines multiple decompilers (JD-GUI, CFR, Procyon, FernFlower).

### Assemblers and Disassemblers

*   **javap:** Comes with JDK, disassembles .class to readable bytecode.
*   **Jasmin:** Assembler for JVM bytecode (you write .j files).
    *   [Jasmin Guide](https://jasmin.sourceforge.net/guide.html)
    *   [Jasmin Example](https://github.com/momohatt/jasmin-example)
    *   [Jasmin JVM Setup on macOS](https://stackoverflow.com/questions/39480167/jasmin-jvm-setup-on-mac-osx)
*   **Krakatau:** Powerful assembler/disassembler for .class and DEX.
*   **Soot:** Framework for analyzing & transforming bytecode.
*   **BCEL:** Apache Byte Code Engineering Library.
*   **jasm:** A Java assembler. (https://github.com/roscopeco/jasm)

### Bytecode Engineering Libraries

*   **ASM:** Low-level bytecode manipulation framework. (https://asm.ow2.io/)
*   **Javassist:** High-level API for runtime bytecode generation. (https://www.javassist.org/)
*   **Byte Buddy:** Modern and powerful library for runtime code generation. (https://bytebuddy.net/)

### Debugging and Profiling Tools

*   **VisualVM:** Profiler + heap/thread analyzer. (https://visualvm.github.io/)
*   **JDK Mission Control (JMC):** Production-grade monitoring & profiling. (https://openjdk.org/projects/jmc/)
*   **Java Flight Recorder (JFR):** Low-overhead profiler built into the JVM. (https://docs.oracle.com/en/java/javase/17/jfapi/)
*   **Async Profiler:** Sampling CPU & allocation profiler. (https://github.com/jvm-profiling-tools/async-profiler)
*   **Arthas:** Alibaba’s JVM diagnostic tool. (https://arthas.aliyun.com/en/)
*   **Jol (Java Object Layout):** Analyze object memory layout in JVM. (https://openjdk.org/projects/code-tools/jol/)
*   **jdb:** Java Debugger (comes with JDK, command-line).
*   **Eclipse Memory Analyzer (MAT):** Heap dump analyzer.
*   **IntelliJ IDEA Debugger:** Full-featured JVM debugger.
*   **HotswapAgent:** Reloads class changes at runtime.
*   **Byteman:** Injects rules into JVM for debugging/tracing.
*   **BTrace:** Safe dynamic tracing of JVM apps.

## JVM-Based Compiler Projects

*   **Tiny Java Compiler:** C++ frontend → Jasmin bytecode. (https://github.com/hehez/Tiny-Java-Compiler)
*   **MiniJava Compiler (JavaCC):** Minimalist Java compiler in Java using JavaCC. (https://github.com/BlackyDrum/mini-java-compiler)
*   **Extended MiniJava Compiler (JFlex + Jasmin):** Full front-end and optimizations. (https://github.com/bhavinshah7/Mini-Java-Compiler)
*   **C/C++ Mini-Java Compiler:** Implemented in C/C++; uses flex, recursive & non-recursive LL(1) and LALR parsing. (https://github.com/greati/mini-java-compiler)
*   **TinyJ:** Parses a tiny subset of Java. (https://github.com/harry1357931/TinyJava-ParseTree-Compiler-execute_VMcode)
*   **Java-based MiniJava to LLVM:** Compiles MiniJava to LLVM IR. (https://github.com/vsakkas/minijava-compiler)
*   [tinyjava](https://github.com/arturo182/tinyjava)

## Alternative JVMs and Related Languages

### JVM Alternatives

*   **Jikes RVM:** Research JVM written in Java. (https://github.com/JikesRVM/JikesRVM)
*   **Maxine VM:** Meta-circular JVM from Oracle Labs. (https://github.com/beehive-lab/Maxine-VM)
*   **Cacao JVM:** Lightweight, research JVM written in C++. (http://www.cacaovm.org/)
*   **GraalVM:** Polyglot VM. (https://www.graalvm.org/)
*   **JamVM:** (https://jamvm.sourceforge.net/)
*   **TakaTuka:** (https://en.wikipedia.org/wiki/TakaTuka)
*   **PreonVM:** (https://en.m.wikipedia.org/wiki/PreonVM)
*   **IKVM.NET:** (https://en.m.wikipedia.org/wiki/IKVM)
*   **LeJOS:** (https://en.m.wikipedia.org/wiki/LeJOS)
*   **NanoVM:** (http://harbaum.org/till/nanovm/index.shtml)
*   **Mika VM:** (https://en.m.wikipedia.org/wiki/Mika_VM)
*   **Kaffe:** (http://www.kaffe.org/)

### Other Languages and Compilers

*   **Forth:**
    *   [JonesForth](https://github.com/phf/forth)
*   **J:**
    *   [J Programming Language](https://www.cs.umb.edu/j--/)
*   **Oberon:**
    *   [Wirth's Home Page](https://people.inf.ethz.ch/wirth/index.html)
    *   [Wirth's Compiler Page with code](https://people.inf.ethz.ch/wirth/CompilerConstruction/)
    *   [Project Oberon](https://web.archive.org/web/20230120051556/http://www.projectoberon.com/)
    *   [Project Oberon (Archive)](https://archive.ph/2lMca)
    *   [Active Oberon](http://oberon2005.oberoncore.ru/paper/p_ao.pdf)
    *   [Oberon Language Report](https://people.inf.ethz.ch/wirth/Oberon/Oberon.Report.pdf)
    *   [Oberon Emulator](https://github.com/schierlm/OberonEmulator)
    *   [oberonc](https://github.com/lboasso/oberonc)
    *   [The School of Niklaus Wirth: The Art of Simplicity](http://pascal.hansotten.com/niklaus-wirth/school-of-wirth/)
*   **Pascal:**
    *   [Free Pascal](https://www.freepascal.org/)
    *   [Turbo Pascal Compiler](https://turbopascal.org/compiler)
*   **Cfront:**
    *   [Cfront 3.0.3](https://github.com/mingodad/cfront-3)
    *   [Cfront 1.2](https://github.com/seyko2/cfront-1)
*   **K Lang (Arthur Whitney):**
    *   [Shakti K Education](https://shakti.com/edu)
    *   [K Book](https://xpqz.github.io/kbook/Introduction.html)
    *   [ksimple GitHub](https://github.com/kparc/ksimple)
    *   [Hacker News Discussion 1](https://news.ycombinator.com/item?id=39026551)
    *   [Hacker News Discussion 2](https://news.ycombinator.com/item?id=38868574)
*   **T3X:**
    *   [T3X Language](http://t3x.org/t3x/book.html)
    *   [T3X Reloaded](http://t3x.org/reload/index.html)
*   **Renjin:** (https://www.renjin.org/)
*   **Python JVM Interpreter:** (https://github.com/gkbrk/python-jvm-interpreter)
*   **BoxLang:** (https://boxlang.ortusbooks.com/)
*   **GCJ (GNU Compiler for Java):**
    *   [GCJ](https://github.com/Zopolis4/gcj)
    *   [January 2003 - GCJ: The GNU Compiler for Java](https://objectcomputing.com/resources/publications/sett/january-2003-gcj-the-gnu-compiler-for-java)

## Code Obfuscation

*   [The International Obfuscated C Code Contest (IOCCC)](https://en.m.wikipedia.org/wiki/International_Obfuscated_C_Code_Contest)
*   [IOCCC Winners](https://www.ioccc.org/years.html)

## Further Reading and Videos

### Articles and Blog Posts

*   [C Isn't a Programming Language Anymore](https://faultlore.com/blah/c-isnt-a-language/)
*   [(How to Write a (Lisp) Interpreter (in Python))](https://norvig.com/lispy.html)
*   [mal - Make a Lisp](https://github.com/kanaka/mal)
*   [Parser Generators vs. Handwritten Parsers: A Survey of 2021](https://notes.eatonphil.com/parser-generators-vs-handwritten-parsers-survey-2021.html)
*   [Hacking Python with Spells from Harry Potter](https://mottaquikarim.github.io/dev/posts/hacking-python-with-spells-from-harry-potter/)
*   [RC Day 24: A tiny VM](https://avi.im/blag/2021/rc-day-24/)
*   [Announcing SquirrelFish](https://webkit.org/blog/189/announcing-squirrelfish/)
*   [wingolog](https://wingolog.org/)
*   [Compile-time vs. Run-time Type](https://search.brave.com/search?q=compile+time+type+vs+runtime+type&source=android&summary=1&conversation=ac116b7b39bbb6b89e5e7a)
*   [What is the difference between a compile-time type vs run-time type for any object?](https://stackoverflow.com/questions/14963943/what-is-the-difference-between-a-compile-time-type-vs-run-time-type-for-any-obje)
*   [Runtime vs. Compile Time](https://www.baeldung.com/cs/runtime-vs-compile-time)
*   [Entity Component System (ECS) Introduction](https://www.simplilearn.com/entity-component-system-introductory-guide-article)
*   [How to design an ECS in Java](https://www.reddit.com/r/roguelikedev/comments/a1ssfz/how_to_design_an_ecs_in_java/)
*   [Compiling Java Code, Executing Bytecode](https://foojay.io/today/compiling-java-code-executing- bytecode/)
*   [Building a Heap from an Array](https://www.geeksforgeeks.org/dsa/building-heap-from-array/)
*   [Building your own JVM Interpreter from Scratch](https://medium.com/%40saikadali/building-your-own-jvm-interpreter-from-scratch-86a085e225b1)
*   [Why we need different JVMs](https://medium.com/@saikadali/why-we-need-different-jvms-f40a177e6e48)

### Videos

*   [Natalie Language](https://www.youtube.com/playlist?list=PLWUx_XkUoGTq-nkbhnk6PN4m109ISo5BX)
*   [Jakt Language Hacking](https://www.youtube.com/watch?v=3RO1Jtve6v8&list=PLMOpZvQB55bf2J-TgMOejaViKhN_VkPdE)
*   [JS Bytecode VM](https://www.youtube.com/playlist?list=PLMOpZvQB55beChggmvk-sUm8X_vSezpqL)
*   [JVM Debugging](https://www.youtube.com/watch?v=q7Q7_ex2KuE)
*   [JVM Debugging with IntelliJ](https://www.youtube.com/watch?v=LBQjLeqJmwc)
*   [Java Debugging in VS Code](https://www.youtube.com/watch?v=N4mbCUh65_4)
*   [Java Debugging](https://www.youtube.com/watch?v=sEEdBLhszuk)
*   [Understanding Java Bytecode](https://www.youtube.com/watch?v=ZID0IJiOJdE)
*   [Java Bytecode Explained](https://www.youtube.com/watch?v=mE0oR9NQefw)
*   [JVM Anatomy Park](https://www.youtube.com/watch?v=8pfixE9aM3Y)
*   [Introduction to JVM Internals](https://www.youtube.com/watch?v=cijr3ARKtxo)
*   [G1 Garbage Collector](https://www.youtube.com/watch?v=5mvQOScXDl0)
*   [Java Memory Model](https://www.youtube.com/watch?v=5_eAJNg4PfI)
*   [Java Performance Tuning](https://www.youtube.com/watch?v=4vIKbXb8V7k)
*   [The Future of the JVM](https.youtube.com/watch?v=BeMi8K0AFAc)
*   [JVM as a Language Platform](https://www.youtube.com/watch?v=ZMjYbnkUYkA)
*   [Adventures in JIT compilation](https://www.youtube.com/watch?v=VYo3p4R66N8)
*   [Compiler vs Interpreter](https://www.youtube.com/watch?v=e2zmmkc5xI0)
*   [How a Compiler Works in 10 Minutes](https://www.youtube.com/watch?v=2-iCwCrvbQk)
*   [Creating a Programming Language](https://www.youtube.com/watch?v=7l9i8Ku2IiY)
*   [Let's Write a Compiler](https://www.youtube.com/watch?v=pWOTpGyVv64)
*   [Compiler Design](https://www.youtube.com/watch?v=rPyqB1l4gko)
*   [How Do Compilers Work?](https://www.youtube.com/watch?v=U63CCB7Itr8)
