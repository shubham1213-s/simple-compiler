SimpleLang Compiler for 8-bit CPU
-------- Overview-------

This project implements a custom compiler for a simple high-level language (SimpleLang) that generates assembly code for an 8-bit CPU.
The generated assembly code is executed and verified using a Verilog-based 8-bit CPU simulator.
The project demonstrates the complete compiler workflow:
Lexical Analysis
Syntax Analysis
Code Generation
Instruction mapping to CPU
Simulation and testing


-------Objectives----------

Convert high-level language programs into low-level assembly instructions.
Map language constructs (arithmetic, expressions, etc.) to CPU instructions.
Verify correctness by running the generated code on an 8-bit CPU simulator.
Provide a clear educational implementation of compiler design concepts.


------ Architecture--------

Lexer – Breaks source code into tokens
Parser – Builds syntax structure (AST)
Code Generator – Produces assembly code
CPU Simulator – Executes the generated code
Verification – Confirms output correctness


------Features-------

Supports arithmetic operations (add, sub, etc.)
Translates high-level constructs into 8-bit CPU instruction set
Modular compiler design (lexer, parser, code generator)
Tested using multiple sample programs
Well-documented design and workflow

---------- Tech Stack--------

Compiler Implementation: C / Python / Java (update as per your project)
CPU Design: Verilog HDL
Simulation: Verilog Testbench
Version Control: Git & GitHub

Run the compiler to generate assembly code
Load the generated code into the 8-bit CPU simulator
Observe program execution through simulation output
🧪 Testing
Several SimpleLang programs were compiled.
Generated assembly code was executed on the 8-bit CPU simulator.
Output was verified against expected results.
