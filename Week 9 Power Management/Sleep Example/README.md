# Sleep Example

Two-step Procedure for sleeping (power-down mode)

1. Set SMCR = 0101 (Mode = power-down and sleep enabled = true)
2. Call the “sleep” instruction. The sleep instruction is one of the 131
instructions in the RISC instruction set of ATmega328p. Assembly
commands can be invoked through inline assembler in C.

use asm("sleep");
