# Chapter 1
## The compilation system

![image-compilation-system](./pic/compilation-system.png)

.c -> .i -> .s -> .o -> 

text -> text -> text -> binary -> binary

The programs that perform the four phases which are preprocessor, compiler, assembler, and linker.

1. Preprocessing phase: modifying the original C program according to directives that begin with the # character
2. Compilation phase: translating the text ﬁle hello.i into the text ﬁle hello.s, which contains an assembly-language program
3. Assembly phase: translating hello.s into machine-language instructions, packaging them in a form known as a relocatable object program, and storing the result in the object ﬁle ```hello.o```
4. Linking phase: handling merging the precompiled object ﬁle called ```printf.o``` with ```hello.o```

## Hardware Organization of a System

![image-hardware-org](./pic/hardware-org.png)

1. Buses
2. I/O Devices
3. Main Memory: Physically, main memory consists of a collection of dynamic random access memory (DRAM) chips.
4. Processor: At its core is a word-sized storage device (or register) called the program counter (PC). There are only a few of these simple operations, and they revolve around main memory, the register ﬁle, and the arithmetic/logic unit (ALU).

## Cache

![image-cache](./pic/cache.png)

The L1 and L2 caches are implemented with a hardware technology known as static random access memory (SRAM).

## Operating System

1. to protect the hardware from misuse by runaway applications
2. to provide applications with simple and uniform mechanisms for manipulating complicated and often wildly different low-level hardware devices

![image-os](./pic/os.png)