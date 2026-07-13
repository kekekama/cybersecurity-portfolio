# PROCESS

## What is
A process is a program in execution.
When you open a program, the operating system creates a process.
The same program can create multiple processes.

## What a process contain
- program code;
- data and variables
- stack;
- heap;
- CPU registers;
- open files and other resources;
- information about the current point of execution.

## Process states
- **Running**: it is currently using the CPU
- **Ready**: it is ready to run, but it is waiting for the CPU
- **waiting/blocked**: iot is waiting for an event, such as user input, data from the internet or a file operation
  Ready --> Running --> Waiting

## Thread
A thread is the smallest unit of execution inside a process.
A process can contain one (main thread) or multiple threads.

The threads inside the same process share:
- program code;
- data;
- heap;
- open files and resources.

Each thread has its own:
- stack;
- CPU registers;
- current poijt of execution (PC)

## Scheduler
The scheduler decides which process or thread can use the CPU.
It chooses a process or thread from the ready state and assigns the CPU to it.
Each process or thread can use the CPU for a shr priod of time called **time slice/time quantum**.

**Concurrency** = only one CPU core  Core1: A-->B-->C-->A

**Parallelism** = multiple CPU cores Core1: Thread A; Core2: Thread B

## Context Switch
...

## PID
...
