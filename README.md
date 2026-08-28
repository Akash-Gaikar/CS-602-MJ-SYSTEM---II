# CS-602-MJ-SYSTEM---II

# System - II

# Assignment: Opcode Check

This program checks the mnemonics and operands used in an assembly program.

The program takes two files:
- Opcode file
- Assembly program file

It checks whether the mnemonic is present in the opcode table and identifies the type of operand.

# Operand Types

- Register
- Constant
- Symbol
- Memory Operand

# Files

- main.cpp - Main program
- preprocessor.h - Preprocesses assembly instructions
- mnemonics_validator.h - Checks mnemonics
- register_validator.h - Checks registers
- operand_validator.h - Checks operand types
- opcode.txt - Opcode table
- registers.txt - Register list
- text.asm - Sample assembly program

# How to Run

```bash
cd Opcode_Check
g++ main.cpp -o assembler
./assembler
