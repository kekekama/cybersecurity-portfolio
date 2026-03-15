# CPU BASICS

## What is
CPU (Central Processing Unit) executes machine instructions.

## Instruction cycle
- **fetch**: using the value of the program counter (PC) to takes the address of the instruction;
              takes the instructions to the Instruction Register (IR).
- **decode**: Control Unit decoded the instruction.
- **execute**: does the instructions.

## CPU components
- Control Unit (does instruction cycle)
- ALU (does calculous)
- Registers (temporary memories)

## Clock Speed
It is the speeding of the CPU (Hertz, Hz).
How many times in a second the CPU could execute a cycle.

## RAM

Composed of Address and Data.
First 4 bits → OPCODE
Last bits → specify address or registers

## Jump

Instruction that changes the order of instructions or skips instructions.
Can be used to create a cycle (loop)

Conditional jumps:
Jump Negative → works if the ALU negative flag = true
Jump If Equal
Jump If Greater

## Halt

Instruction that stops the CPU from executing other instructions.
