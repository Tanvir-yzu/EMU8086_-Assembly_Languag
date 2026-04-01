# Assembly Language Calculator - EMU8086

This project contains an assembly language implementation of a simple calculator using EMU8086 emulator.

## Project Structure

```
calculator/
├── mycode.asm          # Main assembly source code
├── mycode.com          # Compiled executable
├── mycode.com.debug    # Debug information
├── mycode.com.list     # Assembly listing
├── mycode.com.symbol   # Symbol table
└── mycode.com.~asm     # Backup of source file
```

## Requirements

- EMU8086 Emulator (available at https://emu8086.microprocessors.com/)

## How to Run

1. Open EMU8086 emulator
2. Load the `calculator/mycode.asm` file
3. Assemble the code (F9 or Assemble menu)
4. Run the program (F10 or Run menu)

## Features

- Basic arithmetic operations (addition, subtraction, multiplication, division)
- Input handling for numbers
- Output display of results

## Assembly Code Overview

The program is written in 8086 assembly language and demonstrates:
- Register usage
- Stack operations
- Interrupt calls for I/O
- Basic control flow (loops, conditionals)

## Learning Objectives

This project serves as an educational example for:
- Understanding 8086 assembly syntax
- Working with EMU8086 development environment
- Implementing basic calculator logic in low-level code
- Handling user input and output in assembly

## Notes

- The `.com` file is the compiled executable that can be run directly in EMU8086
- Debug files contain information useful for debugging the program
- The symbol file shows memory addresses of labels and variables