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

## ALU (Arithmetic Logic Unit)

- Composed of Arithmetic Unit and Logic Unit

Half Adder

- XOR → Sum

- AND → Carry

Adders

- Half Adder → Sum + Carry

- Full Adder → adds 3 bits (A, B, Carry in)

- Ripple Carry Adder → chain of full adders (e.g. 8-bit)

- Last carry → Overflow
![Here just a full adder](../../01_learning/01_computer-fundamentals/01_cpu/images/full_adder.png)
![Here a 8-bit ripple carry adder](../../01_learning/01_computer-fundamentals/01_cpu/images/8_bit_ripple_carry_adder.png)

Logic Unit

- Performs AND, OR, NOT

ALU components

- Inputs: A, B (8 bits)

- Opcode (4 bits) → selects the operation

- Flags: Overflow, Zero, Negative

- Output: result (8 bits)
