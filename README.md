# Hack Machine Code Disassembler

This project implements a disassembler for the Hack computer architecture from the Nand2Tetris course.

## Overview

A disassembler converts machine code back into assembly language.  
This program reads Hack binary instructions (`.hack` files) and translates them into readable Hack assembly instructions.

## Features

- Parses Hack machine code instructions
- Decodes A-instructions and C-instructions
- Outputs equivalent Hack assembly code

## Example Input Files

The repository includes sample Hack machine code programs:

- Add.hack
- Double.hack
- Loop.hack
- Neg.hack

These files can be used to test the disassembler.

## Technologies

- C#
- .NET
- Hack computer architecture (Nand2Tetris)

  ## How to Run

1. Make sure you have .NET installed.
2. Clone the repository.
3. Build the project:

dotnet build

4. Run the disassembler with a Hack machine code file:

dotnet run Add.hack

## Example

Input (machine code):

0000000000000010
1110110000010000

Output (assembly):

@2
D=A

## Course

Computer Organization (COMPORG)
